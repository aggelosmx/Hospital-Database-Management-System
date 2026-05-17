# 🏥 Hospital Database Management System

## 📌 Project Overview

This project focuses on the **analysis, design, implementation, and management** of a relational database system for hospital administrative staff. The system was developed to support the organization and management of hospital operations, including patients, medical staff, hospital wings, rooms, prescriptions, and pharmaceutical data.

The project follows both **top-down** and **bottom-up** database design approaches and applies normalization techniques up to the **Third Normal Form (3NF)** to ensure data consistency, integrity, and efficiency.

The database was designed using **Oracle SQL Developer Data Modeler** and implemented with **Oracle SQL** and **Oracle APEX**.

---

## 🎯 Objectives

The main objectives of this project are:

- Design a complete relational database for hospital management
- Apply database normalization techniques up to 3NF
- Implement relationships between entities using primary and foreign keys
- Create SQL scripts for table creation and data manipulation
- Develop a functional user interface using Oracle APEX
- Demonstrate efficient storage, retrieval, and management of medical data

---

## 🛠 Technologies Used

- Oracle SQL
- Oracle APEX
- Oracle SQL Developer Data Modeler
- Relational Database Design
- SQL Queries
- Database Normalization (1NF, 2NF, 3NF)

---

## 🧩 System Features

### 👨‍⚕️ Staff Management
- Doctors management
- Nurses management
- Administrative personnel management

### 🏥 Hospital Infrastructure
- Wings management
- Rooms management
- Department organization

### 🧑‍🦽 Patient Management
- Patient registration
- Medical information storage
- Room assignment

### 💊 Prescription & Pharmaceutical Management
- Prescription records
- Medication management
- Drug information tracking

### 📊 Database Operations
- SQL queries
- Data insertion
- Data update and deletion
- Complex relational queries

---

## 🗄 Database Design

The database structure includes:

- Entity-Relationship Diagram (ERD)
- Relational Schema
- Primary & Foreign Keys
- Constraints
- Normalization to 3NF

### Main Entities
- Patients
- Doctors
- Nurses
- Rooms
- Wings
- Prescriptions
- Medications
- Departments

---

## 📂 Project Structure

```bash
Hospital-Database-Management-System/
│
├── README.md
├── sql/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   ├── queries.sql
│   ├── constraints.sql
│   └── views.sql
│
├── docs/
│   ├── ERD/
│   ├── normalization/
│   ├── screenshots/
│   └── report/
│
├── apex/
│   └── apex_export.sql
│
└── assets/
```

---

## 📸 Screenshots

The project includes screenshots of:

- ER diagrams
- Database tables
- SQL queries execution
- Oracle APEX application pages
- Relationships between entities

---

## 💻 Example SQL Query

```sql
SELECT p.patient_name,
       d.doctor_name,
       r.room_number
FROM patients p
JOIN doctors d ON p.doctor_id = d.doctor_id
JOIN rooms r ON p.room_id = r.room_id;
```

---

## 📈 Learning Outcomes

Through this project, the following skills were developed:

- Relational database design
- SQL programming
- Data normalization
- Database management
- Oracle APEX development
- Problem analysis and system organization

---

## 🚀 Future Improvements

Possible future enhancements include:

- Authentication system
- Appointment scheduling
- Medical history tracking
- Reporting dashboard
- Advanced analytics
- Role-based access control

---

## 👨‍💻 Author

**Βαλμίρ Μέχα**

Database Design & Development Project

---

## 📄 License

This project is developed for educational purposes.
