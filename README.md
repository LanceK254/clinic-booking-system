# 🏥 Clinic Booking System - MySQL Database

## 📌 Project Description

This is a complete relational database system for managing a clinic’s core operations including patients, doctors, appointments, medications, and prescriptions.

Built using only **MySQL**, the system models real-world relationships in a clinical setting and enforces data integrity through constraints and relationships (PK, FK, UNIQUE, NOT NULL).

## 🚀 How to Set Up

1. Open MySQL Workbench or your preferred MySQL environment.
2. Create a new schema (e.g., `clinic_db`).
3. Run the SQL script provided in `clinic_booking.sql`.
4. The database will be ready with all necessary tables and constraints.

## 🗂 File Included

- `clinic_booking.sql`: The full database schema with comments.

## 📊 Entity Relationship Diagram (ERD)

Here is a visual representation of the schema:

![ERD Screenshot](link-to-your-screenshot.png)  
_or_  
[View ERD on dbdiagram.io](https://dbdiagram.io/your-link)

## ✅ Features

- One-to-many: Doctors ↔ Specializations
- Many-to-many: Appointments ↔ Medications (via Prescriptions)
- Enforced data constraints: PKs, FKs, UNIQUE, NOT NULL
# clinic-booking-system
