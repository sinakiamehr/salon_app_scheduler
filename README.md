# Salon Appointment Scheduler 💇‍♀️💈

This is a command-line-based **Salon Appointment Scheduler** project built for the freeCodeCamp Relational Database Certification. It uses **PostgreSQL** and **Bash** to create, store, and manage customer appointments.

## 📁 Project Files

- `salon.sh` – The Bash script that runs the interactive appointment scheduler.
- `salon.sql` – A PostgreSQL dump of the completed database (`salon`) with the required tables and example data.
- `example.txt` – A sample interaction output that demonstrates expected behavior for passing tests.

---

## 🎯 Features

- Allows customers to book salon appointments via terminal.
- Stores customer information including phone number and name.
- Checks for returning customers based on phone number.
- Stores and manages services and appointment times.
- Provides a menu to select different salon services.
- Stores all data in a PostgreSQL database.

---

## 🛠 Technologies Used

- **PostgreSQL**
- **Bash**
- **psql** (PostgreSQL CLI)

---

## 📦 How to Use

### 🐘 Create the Database

1. Connect to PostgreSQL:
      ```bash
      psql --username=freecodecamp --dbname=postgres

2.	Create the salon database:
      ```bash 
      CREATE DATABASE salon;
      \c salon

3. Create the required tables (you can also run the SQL dump):
      ```bash 
      psql -U freecodecamp < salon.sql

