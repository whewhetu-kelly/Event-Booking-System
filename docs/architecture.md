# Event Booking System Architecture

## Overview

The application follows a modular client-server architecture consisting of the presentation layer, application layer, and database layer. It supports three primary user roles: Administrator, Organizer, and User.

---

## System Components

### Presentation Layer

Technologies:
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

Responsibilities:
- Event Listings
- Booking Interface
- User Dashboard
- Organizer Dashboard
- Administrator Dashboard

---

### Backend Layer

Technology:
- PHP 8+

Responsibilities:
- Authentication
- Event Management
- Booking Processing
- Organizer Management
- User Management
- Report Generation

---

### Database Layer

Technology:
- MySQL

Stores:
- Users
- Organizers
- Events
- Event Categories
- Bookings
- Notifications
- Reports

---

## System Workflow

Administrator / Organizer / User

↓

Authentication

↓

Event Management

↓

Booking Processing

↓

Database

↓

Dashboard & Reports

---

## Architecture Benefits

- Multi-Role Access Control
- Modular Design
- Scalable Structure
- Responsive User Experience
- Secure Data Management
- Easy Maintenance
