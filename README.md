# 🦷 Dental Clinic Management System (Console Based)
## 📌 Project Overview
The **Dental Clinic Management System** is a console-based application developed using **Python and MySQL**.
This system helps dental clinics efficiently manage patient records, dentist information, appointments, treatments, and billing.
The main objective of this project is to simplify the daily operations of a dental clinic and maintain organized records in a structured database.
This project is developed as part of academic learning to demonstrate the use of **Python programming, database management using MySQL, and console-based application development**.
---
## 🚀 Features
### 👤 Patient Management
* Add new patient details
* View all patient records
* Search patient by ID
* Update patient information
* Delete patient records
### 🦷 Dentist Management
* Add dentist details
* View dentist list
* Store specialization and experience
### 📅 Appointment Management
* Book new appointments
* View scheduled appointments
* Cancel appointments
* Track patient visits
### 💊 Treatment Records
* Store treatment details
* Maintain patient treatment history
* Record treatment cost and notes
### 💳 Billing System
* Generate patient bills
* Store payment information
* Track clinic revenue
### 📊 Reports
* Total number of patients
* Appointment reports
* Treatment history
* Revenue summary
---
## 🛠 Technology Stack
| Technology      | Description                            |
| --------------- | -------------------------------------- |
| Python          | Core programming language              |
| MySQL           | Database for storing clinic data       |
| MySQL Connector | Python library for database connection |
| Git & GitHub    | Version control and project hosting    |
---
## 🗄 Database Structure
Database Name:
```
dental_clinic
```
Tables used in the system:
* patients
* dentists
* appointments
* treatments
* billing
* users (optional for login system)
---
## 📁 Project Structure
```
Dental-Clinic-Management-System
│
├── main.py
├── db_connection.py
│
├── patient.py
├── dentist.py
├── appointment.py
├── treatment.py
├── billing.py
│
├── reports.py
│
├── database.sql
│
└── README.md
```
---
## ⚙️ Installation Guide
### Step 1: Clone the repository
### Step 2: Install required library
```
pip install mysql-connector-python
```
### Step 3: Setup MySQL Database
Create a database in MySQL:
```
CREATE DATABASE dental_clinic;
```
Import the provided SQL file:
```
SOURCE database.sql;
```
### Step 4: Run the program
```
python main.py
```
---
## 📚 Learning Outcomes
Through this project, the following concepts are demonstrated:
* Python programming fundamentals
* Database connectivity with MySQL
* CRUD operations (Create, Read, Update, Delete)
* Console-based application design
* Basic healthcare management system structure
* GitHub project management
---
## 🔮 Future Improvements
Possible future enhancements include:
* Graphical User Interface (GUI)
* Web-based clinic management system
* Appointment reminder system
* PDF bill generation
* Patient login portal
* Data visualization dashboard
---
## 👩‍💻 Author
**Gayatri Padalia**
BCA (Hons.) Artificial Intelligence & Data Science
Graphic Era Hill University, Haldwani
---
## 📄 License
This project is created for **educational purposes**.
