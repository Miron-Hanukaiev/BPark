<h1 align="center">BPARK – Parking Management System</h1>
<p align="center">
Java-based Client-Server Parking Management System
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0fee7b31-3a76-4e92-9369-f23909b3cd85" width="900"/>
</p>

BPARK is a Java-based client-server parking management system developed as an academic project during my third year of Software Engineering studies.
The system simulates a real-world parking management environment, including vehicle entry, reservations, subscriber validation, and parking lot capacity control.

--------------------------------------------------
System Overview

The project follows a client-server architecture and is divided into three main modules:

BPARK – Parking Management System
A Comprehensive Java Client-Server Project

This repository contains the full implementation of BPARK, a Java-based client-server parking management system developed as part of an academic project during our Software Engineering studies.  
The project simulates a real-world parking environment, including subscriber validation, vehicle entry, reservations, and parking lot capacity management.

The system demonstrates practical application of software engineering principles, networking, database integration, and modular system design.

--------------------------------------------------
About the Project

<p align="center">
  <img src="https://github.com/user-attachments/assets/38824411-bcf4-4af7-9475-1e6a3a9d6585" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/99b89853-2ef3-479b-a710-a47a95703c1f" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/11ded1e5-6d7c-4866-95ef-1c897061b1f0" width="700"/>
</p>

BPARK showcases the design and implementation of a distributed system using a client-server architecture.  
The project emphasizes clean separation of concerns, reliable communication, and real-time interaction between system components.

The system was developed to reflect real-life parking management workflows and constraints, combining GUI development, server-side logic, and persistent data storage.

--------------------------------------------------
System Architecture

The project is built using a layered client-server architecture and is divided into three main modules:

- BPARK_Client  
  JavaFX-based client application responsible for user interaction and request handling.

- BPARK_Server  
  Server-side application that processes client requests, manages business logic, handles concurrency, and communicates with the database.

- BPARK_Common  
  Shared module containing data models, message objects, and common utilities used by both client and server.

Communication between client and server is performed over TCP using serialized objects.

--------------------------------------------------
Technologies & Development Environment

Programming Language:
- Java

GUI Framework:
- JavaFX

Networking:
- OCSF (Object Client-Server Framework)

Database:
- MySQL
- JDBC

Architecture & Design:
- Client-Server Architecture
- MVC Pattern
- Layered Architecture
- Object-Oriented Programming (OOP)

Development Tools:
- Eclipse / IntelliJ IDEA
- Git & GitHub
- MySQL Workbench

--------------------------------------------------
Key Features

- Client-server communication using serialized messages
- Subscriber and vehicle validation mechanisms
- Parking lot capacity management
- Reservation handling and conflict prevention
- Persistent storage using MySQL
- Modular and maintainable code structure
- JavaFX graphical user interface
- Concurrency handling on the server side

--------------------------------------------------
Project Structure

```bash
BPARK/
│
├── BPark_Client/      JavaFX client application
├── BPark_Server/      Server-side logic and database access
├── BPark_Common/      Shared models and communication objects
└── README.md
```

--------------------------------------------------
Getting Started

Prerequisites:
- Java JDK 8 or higher
- MySQL Server
- IDE (Eclipse or IntelliJ recommended)
- Git

--------------------------------------------------
Database Setup

1. Create a MySQL database:
   CREATE DATABASE bpark;

2. Import the database schema if provided.

3. Configure database credentials in the server configuration:
   jdbc:mysql://localhost:3306/bpark

--------------------------------------------------
Running the Server

1. Open the project in your IDE
2. Navigate to:
   BPark_Server
3. Run the main server class:
   Server.java

The server will start listening for incoming client connections.

--------------------------------------------------
Running the Client

1. Navigate to:
   BPark_Client
2. Run the JavaFX client main class:
   ClientMain.java
3. Connect to the server using the configured host and port

--------------------------------------------------
Testing and Validation

- Manual testing through client-server interaction
- Validation of concurrent vehicle entry scenarios
- Database state verification after operations
- Defensive input validation and error handling

--------------------------------------------------
Academic Context

This project was developed as part of an academic Software Engineering curriculum and demonstrates:

- Distributed system design
- Real-time client-server communication
- Database-backed applications
- GUI development integrated with backend logic
- Application of software engineering best practices

--------------------------------------------------
Future Enhancements

- Role-based access control
- RESTful API layer
- Automated unit and integration testing
- Improved GUI and user experience
- Deployment-ready configuration

--------------------------------------------------
Authors

Developed by Amit Deri, Ravid Shalev, Eliran Melihov, Liron Zino, Miron Hanukaiev
B.Sc. Software Engineering – Ort Braude College
