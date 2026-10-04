# Event-Management-System-NIBM-Campus

## Event Management System – NIBM Campus

A full-stack web application developed to improve the way student events are organized, managed, and accessed at the NIBM campus.

The system provides a centralized platform where students can view and register for events, while administrators can manage event information and registrations. The application was designed to address the practical challenges of managing campus events through a more organized and accessible digital platform.

The project was developed using **Node.js, Express.js, MongoDB Atlas, HTML, CSS, and JavaScript**, with separate functionality for student and administrator users.

---

## Overview

Managing student events manually can make it difficult to keep track of event information, registrations, participants, and administrative activities.

This project provides a web-based solution that brings these activities into a single system.

The application includes:

* Student and administrator authentication
* Event information management
* Student event registration
* Centralized event information
* User role-based functionality
* MongoDB database integration
* Backend API and server-side processing

The system demonstrates how a full-stack web application can be used to solve a practical problem within a university environment.

---

## Problem Statement

Student events require coordination between organizers, administrators, and participants. When event information and registrations are handled through separate or manual methods, it can become difficult to maintain accurate information and efficiently manage participants.

The Event Management System was developed to provide a centralized platform for:

* Publishing event information
* Managing campus events
* Allowing students to register for events
* Managing registered participants
* Separating student and administrator functionality
* Improving accessibility of event-related information

---

## Objectives

The main objectives of this project are:

1. Develop a centralized web-based platform for NIBM campus events.
2. Provide secure authentication for different types of users.
3. Allow students to view available events and register for them.
4. Allow administrators to create and manage event information.
5. Store event and registration information in a centralized database.
6. Improve the organization and accessibility of campus event information.
7. Apply full-stack web development concepts to a real-world university scenario.

---

## Key Features

### Student Features

Students can use the system to:

* Create/login to their account
* Access available event information
* View event details
* Register for events
* Access relevant event information through a centralized platform

### Administrator Features

Administrators have additional functionality for managing the system, including:

* Administrator authentication
* Event management
* Managing event information
* Monitoring event registrations
* Managing information related to campus events

### Authentication

The system includes authentication functionality for both:

* **Student Users**
* **Administrator Users**

Different user roles provide access to different system functionalities.

---

## System Workflow

```text
                    Event Management System
                              │
             ┌────────────────┴────────────────┐
             │                                 │
             ▼                                 ▼
      Student User                       Administrator
             │                                 │
             ▼                                 ▼
         Login/Register                     Login
             │                                 │
             ▼                                 ▼
       View Events                     Manage Events
             │                                 │
             ▼                                 ▼
      Event Details                   Manage Information
             │                                 │
             ▼                                 ▼
      Register for Event              Monitor Registrations
             │                                 │
             └────────────────┬────────────────┘
                              ▼
                       MongoDB Atlas
                              │
                              ▼
                         Stored Data
```

---

## Application Architecture

The project follows a basic full-stack architecture where the frontend communicates with the backend server, while the backend handles application logic and database operations.

```text
┌──────────────────────────┐
│          Users           │
│                          │
│  Students / Admins       │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│      Web Interface       │
│                          │
│ HTML / CSS / JavaScript  │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│      Express.js          │
│       Backend            │
│                          │
│ Routes / Logic / APIs    │
└────────────┬─────────────┘
             │
             ▼
┌──────────────────────────┐
│       MongoDB Atlas      │
│                          │
│ Users / Events /         │
│ Registration Data        │
└──────────────────────────┘
```

---

## Event Registration Workflow

```text
Student Login
      │
      ▼
View Available Events
      │
      ▼
Select an Event
      │
      ▼
View Event Details
      │
      ▼
Register for Event
      │
      ▼
Registration Stored
      │
      ▼
Database Updated
```

---

## Admin Event Management Workflow

```text
Admin Login
     │
     ▼
Admin Dashboard
     │
     ▼
Create / Update Event
     │
     ▼
Event Information Stored
     │
     ▼
Students Can View Event
     │
     ▼
Student Registrations
     │
     ▼
Admin Can Manage Registration Information
```

---

## Technologies Used

| Technology        | Purpose                                |
| ----------------- | -------------------------------------- |
| **Node.js**       | Backend runtime environment            |
| **Express.js**    | Web server and backend framework       |
| **MongoDB Atlas** | Cloud-based database                   |
| **HTML**          | Web page structure                     |
| **CSS**           | User interface styling                 |
| **JavaScript**    | Frontend functionality and interaction |

---

## Database

The application uses **MongoDB Atlas** as the database platform.

MongoDB provides a flexible document-based database structure suitable for storing application information such as:

* User information
* Authentication-related data
* Event information
* Event registration information

The backend communicates with the database to store and retrieve application data.

> The exact database collections and fields can be updated in this README to match the final implementation of the project.

---

## Backend

The backend was developed using **Node.js and Express.js**.

The backend is responsible for:

* Handling HTTP requests
* Managing application routes
* Processing user-related operations
* Managing event-related operations
* Processing registrations
* Communicating with MongoDB Atlas
* Returning relevant data to the frontend

This project provided practical experience in developing a server-side application and connecting a web interface with a database.

---

## Frontend

The frontend was developed using:

* HTML
* CSS
* JavaScript

The interface provides users with access to the main functions of the application, including authentication, event information, registration, and administration.

JavaScript is used to provide client-side functionality and interaction with the backend.

---

## User Roles

The application separates users according to their responsibilities.

| User Type         | Main Responsibilities                                          |
| ----------------- | -------------------------------------------------------------- |
| **Student**       | View events, access event details, register for events         |
| **Administrator** | Manage events, manage event information, monitor registrations |

This role-based approach helps ensure that administrative functionality is separated from normal student functionality.

---

## Security and Authentication

Authentication functionality was implemented to control access to the application.

The system provides separate login functionality for students and administrators, allowing different users to access functionality based on their role.

For demonstration purposes, sample user credentials are shown in the project demonstration video.

**Note:** The credentials shown in the demonstration are demo credentials only and should not be used as real production credentials.

---

## Project Development Process

The project followed a full-stack development workflow:

```text
Problem Identification
        │
        ▼
System Requirements
        │
        ▼
UI Design
        │
        ▼
Frontend Development
        │
        ▼
Backend Development
        │
        ▼
MongoDB Database Integration
        │
        ▼
Authentication & User Roles
        │
        ▼
Event Management
        │
        ▼
Event Registration
        │
        ▼
Testing & Debugging
        │
        ▼
Final Web Application
```

---

## Main Functional Areas

### 1. User Authentication

Users can authenticate themselves through the application's login functionality.

### 2. Event Management

Administrators can manage event-related information through the system.

### 3. Event Discovery

Students can access available campus events and view relevant information.

### 4. Event Registration

Students can register for events through the web application.

### 5. Database Management

Application data is stored and retrieved through MongoDB Atlas.

### 6. Role-Based Access

Different functionalities are provided depending on whether the user is a student or administrator.

---

## Project Structure

The exact structure may vary depending on the final version of the repository. A typical structure for the project is:

```text
Event-Management-System-NIBM-Campus/
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── views/
│
├── routes/
│
├── models/
│
├── controllers/
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

> Update the structure above if your repository uses different folder or file names.

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Pawarasithumina/Event-Management-System-NIBM-Campus.git
```

### 2. Navigate to the Project

```bash
cd Event-Management-System-NIBM-Campus
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure MongoDB Atlas

Create a MongoDB Atlas database and configure the required database connection in the application.

If environment variables are used, create a `.env` file and add the required configuration.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=3000
```

> Do not upload real database credentials or secrets to GitHub.

### 5. Start the Application

Depending on the project configuration:

```bash
node server.js
```

or:

```bash
npm start
```

Then open the application in your browser using the configured local port.

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Full-stack web development
* Backend development with Node.js
* Express.js application development
* REST/API-based application architecture
* MongoDB database integration
* MongoDB Atlas
* User authentication
* Role-based access control
* Event registration systems
* Frontend development
* Database-driven applications
* Debugging and application testing
* Connecting frontend, backend, and database components

---

## Learning Outcomes

Through this project, I gained practical experience in developing a complete web application rather than working only on individual frontend or backend components.

Key learning outcomes included:

* Understanding full-stack application architecture
* Building backend services using Node.js and Express.js
* Connecting a web application to MongoDB Atlas
* Working with database-driven applications
* Implementing user authentication
* Separating functionality based on user roles
* Developing event registration functionality
* Handling frontend and backend communication
* Understanding how real-world requirements can be translated into software features
* Testing and debugging a multi-component web application

---

## Real-World Application

Although developed as an academic project, the system was designed around a real-world university requirement.

A system of this type can be extended for use by:

* Universities
* Higher education institutes
* Student clubs
* Student societies
* Event organizing committees
* Campus organizations

Possible future functionality could include automated notifications, event reminders, attendance tracking, QR-based event check-in, reporting dashboards, and more advanced administrative controls.

---

## Future Improvements

Potential improvements include:

* Email notifications for event registrations
* Event reminder notifications
* QR-code-based event attendance
* Event search and filtering
* Registration limits and waiting lists
* Event category management
* Student registration history
* Admin analytics dashboard
* Event participation reports
* Improved authentication and password security
* Responsive mobile-first interface
* Deployment to a production cloud environment

---

## Academic Context

This project was developed as part of the **NIBM Higher National Diploma in Computing / Data Science academic coursework** and provided practical experience in full-stack web application development.

The project focused on applying software development concepts to a real-world campus problem and integrating frontend development, backend development, authentication, and database management into one application.

---

## Project Outcome

The completed system provides a centralized platform for managing and accessing NIBM campus events.

It demonstrates how a full-stack application can combine:

**Frontend + Backend + Database + Authentication + Event Management**

to create a practical solution for a real-world organizational requirement.

---

## Contributors

- [@dhamith99](https://github.com/dhamith99)

### Contribution

This project was developed collaboratively, with contributions to the implementation, documentation, and project development process.
