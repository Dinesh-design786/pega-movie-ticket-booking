# 🎬 CineWave — Movie Ticket Booking Management System

<div align="center">

### A Case-Driven Movie Ticket Booking Workflow Built with Pega Platform™

<br>

![Pega Platform](https://img.shields.io/badge/Built%20with-Pega%20Platform-blue)
![Case Management](https://img.shields.io/badge/Domain-Case%20Management-success)
![Data Modeling](https://img.shields.io/badge/Focus-Data%20Modeling-orange)
![Workflow Automation](https://img.shields.io/badge/Focus-Workflow%20Automation-purple)

</div>

---

# 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Solution](#-solution)
- [Project Objectives](#-project-objectives)
- [Technology Stack](#-technology-stack)
- [Application Architecture](#-application-architecture)
- [Case Types](#-case-types)
- [Case Lifecycle](#-case-lifecycle)
- [Data Model](#-data-model)
- [User Stories](#-user-stories)
- [Business Logic](#-business-logic)
- [SLA Configuration](#-sla-configuration)
- [Work Queue Routing](#-work-queue-routing)
- [Notification Flow](#-notification-flow)
- [Application Workflow](#-application-workflow)
- [Testing](#-testing)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Learning Outcomes](#-learning-outcomes)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

# 🎞️ Project Overview

**CineWave** is a Movie Ticket Booking Management application designed using the **Pega Platform™**.

The application manages the complete journey of a movie ticket booking request.

A customer can initiate a booking request, provide movie and show information, check availability, review the calculated booking cost, confirm the booking, and receive confirmation after the booking process is completed.

The application uses **case management**, **data objects**, **business rules**, **service-level agreements**, **work queues**, and **automated correspondence** to create a structured booking workflow.

---

# 🚨 Problem Statement

Movie ticket booking requests can become difficult to manage when the process depends on:

- Manual communication
- Email-based requests
- Offline tracking
- Manual seat availability verification
- Manual booking status updates
- Delayed customer communication

These approaches can lead to several problems.

## Common Challenges

### 📩 Lack of Centralized Tracking

Booking requests may be spread across multiple systems or communication channels.

This makes it difficult to determine:

- Which requests are pending
- Which requests are confirmed
- Which bookings require action
- Who is responsible for processing a request

---

### ⏳ Delays in Booking Processing

Without an automated workflow, staff members must manually review each request.

This can result in:

- Delayed availability checks
- Delayed booking confirmation
- Delayed customer communication

---

### 💰 Manual Cost Calculation

The booking price may need to be calculated manually.

For example:

```text
Ticket Price × Number of Tickets
