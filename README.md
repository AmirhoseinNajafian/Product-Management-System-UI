<div align="center">

# AWMIR.IR

### Personal Music & Content Platform

**Music · Content · Identity · Backend · Administration**

<br>

<a href="https://awmir.ir">
  <img src="https://img.shields.io/badge/Visit%20AWMIR.IR-111111?style=for-the-badge" alt="Visit AWMIR.IR">
</a>
&nbsp;
<a href="./README.fa.md">
  <img src="https://img.shields.io/badge/🇮🇷%20فارسی-111111?style=for-the-badge" alt="Persian README">
</a>

</div>

---

<div align="center">

<img src="./docs/screenshots/home.png" alt="AWMIR.IR Homepage" width="100%">

</div>

---

## About

**AWMIR.IR** is a personal music and content platform built around **music, identity, content, and a custom backend-driven administration system**.

Rather than following the structure of a conventional corporate website or traditional media platform, AWMIR is designed as a unified digital experience where music, personal content, visual identity, and platform infrastructure work together as one system.

The platform combines:

* 🎵 Music and audio experiences
* ✍️ Personal articles and content
* 👤 Personal identity and presentation
* ⚙️ Custom backend infrastructure
* 🛠️ Dedicated administration system
* 🗄️ Persistent data management

AWMIR is both a **real-world digital platform** and a **full-stack development project** focused on creating a personalized, content-driven web experience.

---

# Platform

AWMIR brings multiple experiences together inside a single personal platform.

### Music

A dedicated environment for discovering and listening to original music.

### Content

A personal publishing layer for articles, written content, and project-related material.

### Identity

A digital space for presenting the creator, their work, interests, and visual identity.

### Administration

A dedicated management environment for controlling platform content and configuration.

---

# Public Experience

The public side of AWMIR is built around four core ideas:

**Identity · Atmosphere · Music · Story**

The interface intentionally avoids the appearance of a generic CMS or conventional corporate website.

---

## Homepage

<div align="center">

<img src="./docs/screenshots/home.png" alt="AWMIR Homepage" width="100%">

</div>

The homepage is the primary entry point to the AWMIR experience.

It introduces the platform's visual identity while providing access to featured content, music, and the main areas of the website.

---

## Login

<div align="center">

<img src="./docs/screenshots/login.png" alt="AWMIR Music" width="100%">

</div>

The registration section, which is connected to the database and stores each person's information securely.

---

## profile

<div align="center">

<img src="./docs/screenshots/profile.png" alt="AWMIR Music Player" width="100%">

</div>

The profile section, where each person can customize or modify their profile.

They can also edit their account details, such as their password and username, and change the site's language.

---

# Administration

## The System Behind AWMIR

The public website represents only one layer of the platform.

Behind the interface is a dedicated administration system designed to provide centralized control over the platform's content and configuration.

---

## Admin Dashboard

<div align="center">

<img src="./docs/screenshots/admin.png" alt="AWMIR Administration Dashboard" width="100%">

</div>

The administration dashboard acts as the central control environment for AWMIR.

Depending on the current implementation, the administration system can provide management capabilities for areas such as:

* Music
* Articles
* Media
* Featured content
* Platform configuration
* Existing content
* Administrative operations

The goal is to keep content management centralized, structured, and separated from the public experience.

---

# System Architecture

<div align="center">

<img src="./docs/screenshots/architecture.png" alt="AWMIR System Architecture" width="100%">

</div>

AWMIR follows a layered architecture that separates the public experience, administration, application logic, and persistent data.

```text
Public Website ──┐
                 │
                 ▼
                API
                 │
                 ▼
              Backend
                 │
                 ▼
              Database
                 ▲
                 │
Admin Panel ─────┘
```

### Public Website

Provides the visitor-facing experience for music, content, and personal information.

### Administration Panel

Provides controlled access to platform management and content operations.

### API & Backend

Handle communication, application logic, authentication, and platform operations.

### Database

Provides persistent storage for the platform's content and application data.

This separation keeps the presentation layer independent from the underlying application and data management.

---

# Architecture Principles

AWMIR is built around a few core principles:

### Separation of Concerns

Presentation, application logic, administration, and data are kept as separate responsibilities.

### Centralized Management

Platform content is managed through a dedicated administration environment.

### Backend-Driven Content

Content can be managed independently from the public presentation layer.

### Extensibility

The architecture can evolve as additional platform features are introduced.

### Maintainability

The separation between interfaces, backend logic, and data makes the platform easier to maintain and extend.

---

# Authentication & Security

Administrative functionality is separated from the public visitor experience through authentication and authorization.

The conceptual flow is:

```text
Administrator
      │
      ▼
Authentication
      │
      ▼
Authorization
      │
      ▼
Administration
      │
      ▼
Backend
```

Production environments should follow standard security practices including:

* Protected administrative routes
* Server-side validation
* Secure environment configuration
* Safe file handling
* Database protection
* HTTPS
* Rate limiting
* Secure headers
* Logging
* Dependency updates
* Backups

---

# Data

The platform's data layer covers several core areas:

| Area           | Purpose                                 |
| -------------- | --------------------------------------- |
| Music          | Tracks and music-related information    |
| Articles       | Personal written content                |
| Media          | Images, files, and other assets         |
| Administration | Administrative access and configuration |

The exact implementation and schema may evolve as the platform develops.

---

# Why a Custom Backend?

AWMIR uses a custom backend to maintain direct control over the structure and behavior of the platform.

Instead of relying entirely on a generic CMS, the platform can define its own:

* Data structures
* Business logic
* Content workflows
* Administration experience
* API behavior
* Authentication model
* Platform-specific functionality
* Future integrations

This makes the backend an integral part of the product rather than simply an invisible service behind the website.

---

# Design Philosophy

AWMIR intentionally avoids looking like a generic corporate website or traditional CMS.

The public experience focuses on:

**Identity**

**Music**

**Atmosphere**

**Story**

While the administration experience focuses on:

**Control**

**Structure**

**Content**

**Management**

This separation allows the public interface to remain expressive and immersive while the underlying system remains organized and maintainable.

---

# Visual Direction

The visual identity of AWMIR is built around a modern and distinctive digital aesthetic.

The design language focuses on:

* Minimal interfaces
* Immersive layouts
* Strong visual identity
* Music-oriented interactions
* Clear information hierarchy
* Modern typography
* Smooth interaction patterns
* Personal branding
* Structured content presentation

The goal is not simply to create a modern website, but to create a digital environment that feels connected to the identity of the project.

---

# Reference Project

AWMIR can also serve as a practical reference for developers interested in building similar personal platforms.

The project demonstrates how a personal website can evolve into a complete digital platform consisting of:

```text
Personal Website
       +
Music System
       +
Content System
       +
Custom Backend
       +
Database
       +
Administration Panel
```

The same concepts can be adapted for:

* Artist websites
* Musician platforms
* Creator portfolios
* Personal media websites
* Publishing platforms
* Content-driven websites
* Custom CMS projects
* Personal digital platforms

AWMIR is not intended to represent a universal architecture.

It represents one practical approach to building a personal platform around a custom backend and administration system.

---

# Documentation

Visual documentation is intentionally kept simple and focused.

```text
docs/
└── screenshots/
    ├── home.png
    ├── music.png
    ├── player.png
    ├── admin.png
    └── architecture.png
```

These five visuals cover the main aspects of the platform:

**Public Experience → Music → Player → Administration → Architecture**

---

# Roadmap

Future development may include:

* [ ] Expanded analytics
* [ ] More granular administration permissions
* [ ] Advanced media management
* [ ] Improved content workflows
* [ ] Extended music functionality
* [ ] Additional API capabilities
* [ ] Performance improvements
* [ ] Automated deployment
* [ ] Expanded security controls
* [ ] Extended technical documentation

---

# Live Website

<div align="center">

### <a href="https://awmir.ir">AWMIR.IR</a>

Personal Music & Content Platform

</div>

---

# Project

**AWMIR.IR**

**Personal Music & Content Platform**

Built around:

**Music · Content · Identity · Backend · Administration**

---

<div align="center">

### AWMIR

**More Than Just a Website.**

<br>

<a href="https://awmir.ir">Website</a>
 ·  <a href="./README.fa.md">Persian README</a>

</div>
