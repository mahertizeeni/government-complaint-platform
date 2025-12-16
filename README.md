# Government Complaints Platform

## 📌 Overview

A web-based government complaints platform built with Laravel, designed to allow citizens to submit complaints without the need for authentication, while enabling government administrators to manage, track, and respond to complaints efficiently.

The system focuses on simplicity for citizens and strong administrative control on the backend.

---

## ⚙️ Tech Stack

* Laravel
* PHP
* MySQL
* RESTful API
* Email Notifications
* AI-powered Smart Chat

---

## ✨ Key Features

* Complaint submission without user authentication
* Full Arabic interface
* Automatic complaint classification by city and government entity
* Admin dashboard for managing complaints
* Complaint status tracking and workflow management
* Email notifications for complaint updates
* API-ready architecture

---

## 🧱 Architecture & Design

* Clean MVC architecture
* Service layer for business logic
* Context-aware smart chat service
* Validation using Form Requests
* Centralized response handling

---

## 🔐 Security Considerations

* Rate limiting for complaint submissions
* Input validation and sanitization
* Admin authentication and role-based access

---

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies

   ```bash
   composer install
   ```
3. Configure `.env`
4. Run migrations

   ```bash
   php artisan migrate
   ```
5. Start the server

   ```bash
   php artisan serve
   ```

---

## 📄 License

This project is intended for educational and demonstration purposes.
