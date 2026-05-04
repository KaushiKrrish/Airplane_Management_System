# Airplane_Management_System
Overview

The Airline Management System is a desktop-based application developed using Java. It provides functionalities for managing airline operations such as customer details, flight booking, cancellations, and boarding pass generation.
This project demonstrates core concepts of Java Swing (GUI), Object-Oriented Programming, and Database Connectivity (JDBC).

Features
1. User Login System
2. Add Customer Details
3. Book Flight Tickets
4. Cancel Reservations
5. Generate Boarding Pass
6. View Flight Information
7. Journey Details Tracking
8. Tech Stack

Language: Java
GUI: Java Swing
Database: MySQL
Connectivity: JDBC

Setup Instructions
1. Clone / Download Project
git clone <your-repo-link>
2. Open in IDE
Open the project in NetBeans / IntelliJ IDEA / Eclipse
3. Configure Database
Install MySQL
Create a database (example: airline_db)
Create required tables (you may need to inspect Conn.java for schema usage)
Update database credentials in:
Conn.java

Example:

Connection c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/airline_db",
    "username",
    "password"
);
4. Add MySQL Connector
Download MySQL JDBC Driver (mysql-connector-java)
Add it to your project libraries
5. Run the Application
Run:
Login.java
This will launch the main system

Key Components
Login.java → Entry point with authentication
Home.java → Dashboard
BookFlight.java → Ticket booking system
Cancel.java → Ticket cancellation
BoardingPass.java → Boarding pass generation
Conn.java → Database connection handler

Notes
Ensure MySQL service is running before starting the app
Update DB credentials properly
GUI is built using Swing (desktop-based, not web)

Future Improvements
Convert to web-based system (Spring Boot / React)
Add payment gateway integration
Improve UI/UX design
Add real-time flight APIs
👨‍💻 Author

Developed as a learning project for understanding Java GUI and database integration.
