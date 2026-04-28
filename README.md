📘 Description

This project is a Hospital Management System database designed using SQL. It manages hospital data including departments, doctors, patients, nurses, rooms, appointments, admissions, and prescriptions. The system is fully normalized up to 3NF and ensures efficient data storage and retrieval.

🎯 Objectives
To design a structured hospital database
To reduce data redundancy using normalization
To implement relationships using primary and foreign keys
To perform data operations using SQL queries
🧱 Database Structure

The database consists of the following tables:

Department98
Doctor98
Patient98
Nurse98
Room98
Appointment98
Admission98
Prescription98
🔗 Relationships
Department → Doctor, Nurse, Room (1:N)
Doctor → Appointment, Admission, Prescription (1:N)
Patient → Appointment, Admission, Prescription (1:N)
Room → Admission (1:N)
⚙️ Features
Use of Primary Keys and Foreign Keys
Implementation of Joins (INNER, LEFT, RIGHT, FULL)
Use of Views for simplified queries
Group By and Aggregate Functions
Subqueries for advanced filtering
Indexing for performance optimization
🛠️ Technologies Used
Oracle SQL
Relational Database Design
ER Diagram
▶️ How to Run
Open Oracle SQL / SQL Developer
Run the CREATE TABLE statements
Insert data using INSERT queries
Execute SELECT queries for results
📊 Normalization

All tables are normalized up to Third Normal Form (3NF), ensuring no redundancy and proper dependency management.
