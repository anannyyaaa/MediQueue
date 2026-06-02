# MediQueue# MediQueue

## Overview

MediQueue is a web application designed to reduce overcrowding and long waiting times in government hospitals. The platform allows patients to book appointments online, receive queue updates, and get notifications about their expected consultation time.

The goal is to make hospital visits more organized, reduce unnecessary waiting, and improve the overall patient experience.

---

## Problem Statement

Government hospitals often experience:

* Long waiting queues
* Lack of real-time queue information
* Patients spending hours waiting for their turn
* Poor communication regarding appointment status

MediQueue aims to solve these issues by digitizing the appointment and queue management process.

---

## Features

### Patient Features

* User Registration and Login
* Book Hospital Appointments
* View Upcoming Appointments
* Track Queue Position
* Receive Appointment Notifications
* View Estimated Waiting Time

### Admin Features

* Manage Patient Appointments
* Update Queue Status
* View Daily Appointments
* Monitor Patient Flow

---

## Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT Authentication

### Notifications

* WhatsApp API / SMS API (Optional)

---

## System Workflow

1. Patient registers and logs into the platform.
2. Patient selects a hospital and books an appointment.
3. Appointment details are stored in the database.
4. Admin manages and updates the queue.
5. Patients receive real-time updates about their queue position.
6. Patients arrive closer to their consultation time, reducing waiting hours.

---

## Future Improvements

* AI-based waiting time prediction
* Multi-hospital support
* Doctor availability tracking
* Voice assistant for elderly users
* Mobile application
* Integration with government health systems

---

## Installation

### Navigate to Project Directory

```bash
cd mediqueue
```

### Install Dependencies

```bash
npm install
```

### Start Backend Server

```bash
npm run server
```

### Start Frontend

```bash
npm run dev
```

---

## Project Structure

```bash
mediqueue/
│
├── client/
│   ├── src/
│   ├── components/
│   └── pages/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── middleware/
│
├── package.json
└── README.md
```

---

## Learning Outcomes

Through this project, I learned:

* Full Stack Web Development
* REST API Design
* Authentication and Authorization
* Database Management with MongoDB
* Real-world Problem Solving
* Frontend-Backend Integration

---

## Author

Developed as a project to improve healthcare accessibility and reduce hospital waiting times through technology.
