# CIS2356PROJ-1
# 📚 Library Management System

## 🏛 Project Overview
This is the final project for **CIS 2368 Spring 2025**, implementing a **Library Management System**. The system allows users to:
- Manage customers, books, and borrow records.
- Perform CRUD operations (Create, Read, Update, Delete) for books and customers.
- Track borrowed books and automatically calculate late fees.
- Provide a web interface for managing the library.

## 🛠 Tech Stack
- **Backend:** Python Flask (REST API)
- **Frontend:** JavaScript (EJS)
- **Database:** MySQL / PostgreSQL
- **Testing:** Postman for API testing
- **Deployment:** (Optional for extra credit) AWS

---

## 🚀 Features
### 📚 Book Management
- View, add, edit, and delete books.
- Status tracking (Available / Unavailable).

### 👥 Customer Management
- Add, update, and remove customers.
- Secure password storage with hashing.

### 🔄 Borrow & Return System
- Borrow books (only one per customer at a time).
- Return books and auto-calculate **$1 per day** late fee after 10 days.

---
