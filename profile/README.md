# EduReach

EduReach is a software system with a learner-facing mobile application, a backend API, and an administrative dashboard. It provides an educational resource library where students can discover, read, download, and track learning materials, while administrators manage content and users.

## Overview

This workspace is organized into three repositories, each responsible for a separate part of the system.

## System Architecture

```yaml
Users
  |
  v
Flutter Frontend Application
  |
  v
Spring Boot Backend API
  |
  v
PostgreSQL Database

Administrators
  |
  v
React Admin Dashboard
  |
  v
Spring Boot Backend API
```

## Repositories

| Repository | Description |
| --- | --- |
| [Frontend](edureach_frontend/frontend/README.md) | Flutter learner application for authentication, resource discovery, downloads, offline access, bookmarks, progress, ratings, and notifications. |
| [Backend](edureach_backend/README.md) | Spring Boot REST API for business logic, JWT authentication, resource management, PostgreSQL persistence, and integrations. |
| [Dashboard](edureach_admin/README.md) | React administrative interface for managing resources, subjects, levels, students, and notifications. |

## Tech Stack

- **Frontend:** Flutter, Dart, Riverpod, GoRouter, Dio, Firebase Cloud Messaging
- **Backend:** Java 21, Spring Boot, Spring Security, Spring Data JPA, Flyway, Maven
- **Dashboard:** React, TypeScript, Vite
- **Database:** PostgreSQL
- **Deployment:** Docker and Railway configuration for the backend; frontend and dashboard configuration reference a deployed Render API

## Getting Started

1. Configure PostgreSQL and the backend environment variables.
2. Start the backend API.
3. Configure and start the Flutter frontend with the backend URL.
4. Configure and start the admin dashboard with the backend URL.

## Documentation

For installation instructions, environment configuration, API documentation, and development guidance, refer to the README in each repository above.

## License

No license file is included in this workspace.
# .github
