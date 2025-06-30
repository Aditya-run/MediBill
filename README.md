# MediBill

A full-stack billing and sales automation system for pharmaceutical businesses. Designed to simplify daily sales operations, reduce manual invoicing errors, and provide an intuitive POS-like interface for admins.

---
Screen Shorts![Screenshot 2025-06-30 022737](https://github.com/user-attachments/assets/b82c7f0a-9aa1-4a07-8479-9d063f5bbac0)



## 📌 Features

- Secure admin login
- Dashboard with daily sales overview and recent orders
- POS-style billing interface with cart management
- Customer details form with payment mode selection (Cash/UPI)
- Category management for organizing items
- Item management (CRUD)
- User management for admin control
- Order history with filtering and details

---

## ⚙️ Tech Stack

### Frontend
- ReactJS
- Bootstrap (for responsive UI)

### Backend
- Spring Boot
- Spring Data JPA

### Database
- MySQL

---

## 📂 Project Structure
```
MediBill/
├── client/ # React frontend
└── server/ # Spring Boot backend

```
---

## 🧭 Setup Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Aditya-run/MediBill.git
cd MediBill
```
2️⃣ Frontend Setup
```bash

cd client
npm install
npm start
```
Runs on: http://localhost:3000

3️⃣ Backend Setup
Open server in your IDE

Configure MySQL in application.properties

Build and run:
```

./mvnw spring-boot:run
```
Runs on: http://localhost:8080

⚡ Database Configuration
Create a database (e.g., medibill_db) in MySQL

Example application.properties:
```
spring.datasource.url=jdbc:mysql://localhost:3306/medibill_db
spring.datasource.username=root
spring.datasource.password=yourpassword
```
🙏 Acknowledgements
Huge thanks to Engineer Talks With Bhushan YouTube channel for inspiration and teaching the basics of this stack
