# 🏥 Mustafa Trust Hospital Database

This repository contains the **Mustafa Trust Hospital Database**, designed to manage and organize hospital operations, including patient records, doctors, appointments, billing, medical inventory, and staff.  
It is part of the **Mustafa Trust Foundation** initiative to modernize healthcare management.

---

## 📌 Overview
The database is built using **SQL** and provides structured storage for hospital-related data.  
It supports essential hospital workflows such as patient registration, doctor assignment, scheduling, prescriptions, test results, and billing.

---

## 🚀 Features
- 👨‍⚕️ Manage patients, doctors, staff, and departments  
- 📅 Appointment scheduling with doctors  
- 💊 Prescription management with dosage and duration  
- 🧪 Store medical test results for patients  
- 🏥 Room and ward allocation  
- 💵 Billing system with insurance provider integration  
- 🔐 User authentication with roles (Admin, Doctor, Staff)  
- 📦 Medicine inventory and supply tracking  

---

## 📂 Database Schema
The database includes the following main tables:

- **patients** – Stores patient details (name, DOB, gender, contact, address)  
- **doctors** – Doctor details with specialization and department assignment  
- **appointments** – Links patients and doctors with appointment details  
- **prescriptions** – Medicines prescribed to patients by doctors  
- **medical_records** – History of treatments and diagnoses  
- **test_results** – Results of lab tests for patients  
- **schedules** – Doctor availability and duty schedules  
- **staff** – Hospital staff information  
- **rooms** – Patient room allocation  
- **billing** – Manages patient bills and payments  
- **insurance_providers** – Insurance provider details with packages  
- **users** – Authentication and role-based access control  
- **auxiliary_services** – Additional hospital services (like nursing, tests, etc.)  
- **medicines** – Medicine inventory with stock and dosage  

---

## 🛠️ Tech Stack
- **Database**: SQL (MySQL / MariaDB / PostgreSQL)  
- **Tools**: MySQL Workbench (for ERD), phpMyAdmin (optional), or any SQL client  

---

## ⚡ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mustafa-trust-hospital-database.git
