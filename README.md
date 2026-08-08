# 🚆 Railway Reservation System

A **Core Java Console-Based Railway Reservation System** that allows users to register, log in, view available trains, book tickets, cancel bookings, and manage reservations. This project demonstrates Object-Oriented Programming (OOP), Java Collections, and modular application design.

---

## 📌 Project Overview

The Railway Reservation System is a console-based application developed using **Core Java**. It simulates the basic functionalities of an online railway reservation platform.

The application provides a simple menu-driven interface for users to register, log in, book train tickets, cancel bookings, and view reservation details.

---

## ✨ Features

- 👤 User Registration
- 🔐 User Login & Logout
- 🚆 View Available Trains
- 🎫 Book Train Tickets
- ❌ Cancel Tickets
- 📄 View Booked Tickets
- 🔍 Search Trains
- 💺 Seat Availability Check
- 📋 Menu-Driven Console Interface
- ⚡ Fast In-Memory Data Management using Java Collections

---

## 🛠️ Technologies Used

- Java
- Core Java
- Object-Oriented Programming (OOP)
- Java Collections Framework
- IntelliJ IDEA

---

## 📁 Project Structure

```
RailwayReservationSystem
│
├── src
│   ├── Main.java
│   └── com
│       └── achyuta
│           └── railwayreservation
│               ├── BookingService.java
│               ├── IRCTCAPP.java
│               ├── Ticket.java
│               ├── Train.java
│               ├── User.java
│               └── UserService.java
│
├── .gitignore
└── README.md
```

---

## 🏗️ Project Architecture

```
                 +--------------------+
                 |      Main.java     |
                 +---------+----------+
                           |
                           v
                 +--------------------+
                 |    IRCTCAPP.java   |
                 +---------+----------+
                           |
        +------------------+------------------+
        |                                     |
        v                                     v
+--------------------+              +----------------------+
|   UserService.java |              | BookingService.java  |
+---------+----------+              +----------+-----------+
          |                                    |
          v                                    v
+--------------------+              +----------------------+
|     User.java      |              |     Ticket.java      |
+--------------------+              +----------------------+
                           |
                           v
                    +--------------+
                    |  Train.java  |
                    +--------------+
```

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/AchyutaBiswal/railway-reservation-system.git
```

### Open the Project

Open the project in IntelliJ IDEA or Eclipse.

### Compile

Compile all Java source files.

### Run

Run:

```
Main.java
```

or

```
IRCTCAPP.java
```

(depending on your project entry point)

---

## 💻 Sample Menu

```
==============================
 Railway Reservation System
==============================

1. Register
2. Login
3. View Trains
4. Book Ticket
5. Cancel Ticket
6. View My Tickets
7. Logout
8. Exit

Enter your choice:
```

---

## 📚 Object-Oriented Concepts Used

- Classes & Objects
- Encapsulation
- Constructors
- Method Overloading
- Packages
- Collections Framework
- ArrayList
- HashMap
- Exception Handling
- Modular Programming

---

## 📂 Modules

### User Module

- Register User
- Login
- Logout

### Train Module

- Display Trains
- Search Trains
- Seat Availability

### Booking Module

- Book Ticket
- Cancel Ticket
- View Tickets

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Core Java Programming
- OOP Concepts
- Java Collections
- Console-Based Application Development
- Git & GitHub
- Project Structure and Code Organization

---

## 🔮 Future Enhancements

- Database Integration (MySQL)
- JDBC Connectivity
- Spring Boot REST APIs
- Admin Panel
- Password Encryption
- Online Payment Integration
- Email Notifications
- PDF Ticket Generation
- GUI using JavaFX

---

## 👨‍💻 Author

**Achyuta Biswal**

B.Tech – Computer Science & Engineering

Java Backend Developer | Spring Boot | JDBC | REST APIs | Generative AI Enthusiast

GitHub:
https://github.com/AchyutaBiswal

LinkedIn:
https://www.linkedin.com/in/achyuta-biswal

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is developed for educational and learning purposes.
