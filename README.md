# SQL_Project
# Air India Management System - SQL Project

##  Project Overview

This project simulates an airline database system for **Air India**, built using **MySQL**. It demonstrates how real-world airline operations—such as managing flights, passengers, bookings, and staff—can be efficiently handled using **relational databases** and **SQL JOIN operations**.

## 🛫 Objective

To develop a database that manages and retrieves meaningful airline-related information by linking multiple tables using SQL JOINs and subqueries.

---

##  Database Design

The project includes **4 interlinked tables**:

1. **Flights**
   - `FlightID` (Primary Key)
   - `Source`
   - `Destination`
   - `Departure Time`

2. **Passengers**
   - `PassengerID` (Primary Key)
   - `Name`
   - `Email`

3. **Bookings**
   - `BookingID` (Primary Key)
   - `FlightID` (Foreign Key)
   - `PassengerID` (Foreign Key)
   - `Seat Number`

4. **Staff**
   - `StaffID` (Primary Key)
   - `Name`
   - `FlightID` (Foreign Key)
   - `Role` (e.g., Pilot, Cabin Crew)

---

## 🔗 ER Diagram

The ER Diagram illustrates the relationships between the above entities. It ensures:
- One-to-many relationship from Flight to Bookings
- One-to-many relationship from Flight to Staff
- One-to-many relationship from Passenger to Bookings

---

##  Key Features

- Use of **INNER JOIN** to combine data across multiple tables
- Implementation of **subqueries** to fetch complex information
- Demonstrates how **foreign keys** maintain relational integrity

---

##  Example Queries

- Get passenger names who are on flights piloted by a specific pilot
- Find seat number booked by a specific passenger
- Display all bookings with passenger and flight details

---

##  Conclusion

This project demonstrates the practical use of SQL in real-world scenarios like airline management. It helps visualize how relational databases support decision-making by providing easy access to combined, accurate data.

---

##  Tech Stack

- **Database:** MySQL
- **Tool:** MySQL Workbench
- **Language:** SQL

---

##  Author

**Maithili Ahire**

---

