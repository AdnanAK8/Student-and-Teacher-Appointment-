#  Student-Teacher Booking Appointment System

A web-based system that facilitates scheduling and communication between students and teachers with dedicated roles, authentication, and Firebase integration.

---

##  Problem Statement

Appointment systems — whether traditional or online — are essential in many sectors. In educational institutions, managing appointments between students and teachers can be challenging without a streamlined platform.

This project proposes a **web-based student-teacher appointment booking system** that allows users to:

- Book and manage appointments efficiently
- Reduce unnecessary wait times
- Provide a smooth communication channel via messages
- Access their dashboard from anywhere via web/mobile devices

---

## Technologies Used

| Technology | Description                    |
|------------|--------------------------------|
| HTML/CSS   | Frontend Design & Layout       |
| JavaScript | Logic, Firebase Integration    |
| Firebase   | Authentication & Firestore DB  |
| Logging    | Action-based event logging     |

---

##  System Modules

###  Admin
- Add/Update/Delete Teacher
- Approve Student Registrations

### Teacher
- Login/Logout
- Schedule & Approve Appointments
- View & Reply to Messages
- View All Appointments

###  Student
- Register/Login
- Search Teacher by Subject
- Book Appointment
- Send Message to Teacher

---

##  System Architecture

##Frontend (HTML/CSS/JS) ↓ Firebase Auth ←→ Firestore DB ↓ Role-based Routing (Student / Teacher / Admin Dashboard

## Project Evaluation Metrics

| Metric          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Code Quality  | Modular, clean, maintainable JS code using functions for separation of logic |
|  Database       | Real-time Firestore database for user, appointment & message collections   |
|  Logging        | Logging added for all user actions via `console.log()` or custom functions |
|  Deployment     | Can be hosted on Firebase Hosting / Localhost                               |

---

## Project Workflow

### Authentication
- Firebase Email/Password login for all users
- Role-based dashboards (Student / Teacher / Admin)

###  Appointments
- Students select teachers and propose appointment time
- Teachers can approve/cancel requests

### Messaging
- Students can send message with appointment purpose
- Teachers can view all messages from students

---

## Setup & Execution

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-username/student-teacher-booking.git
   cd student-teacher-booking


