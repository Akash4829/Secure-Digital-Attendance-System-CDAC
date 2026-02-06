# Secure Digital Attendance System

A full-stack web application for managing and tracking attendance securely using modern technologies.

---

## 🚀 Tech Stack

### Backend

* Java
* Spring Boot
* Spring Security
* JWT Authentication
* Maven
* MySQL

### Frontend

* React (Vite)
* Axios
* Bootstrap / CSS

---

## ✨ Features

* User registration and login
* JWT-based authentication
* Role-based access control
* Attendance marking and tracking
* Admin dashboard
* OTP-based password reset via email
* Secure RESTful APIs

---

## 📁 Project Structure

```
Secure-Digital-Attendance-System-CDAC
│
├── Backend/     → Spring Boot REST API
└── Frontend/    → React (Vite) user interface
```

---

## ⚙️ Backend Setup

### Prerequisites

* Java 17+
* Maven
* MySQL

### Steps

```bash
cd Backend
mvn clean install
mvn spring-boot:run
```

The backend will start at:

```
http://localhost:8080
```

---

## 💻 Frontend Setup

### Prerequisites

* Node.js (v18+ recommended)

### Steps

```bash
cd Frontend
npm install
npm run dev
```

The frontend will start at:

```
http://localhost:5173
```

---

## 🗄️ Database Configuration

Update your database credentials in:

```
Backend/src/main/resources/application-local.properties
```

Example:

```properties
spring.datasource.username=your_db_user
spring.datasource.password=your_db_password
```

---

## 🔐 Environment & Security Notes

* Do **not** commit real passwords or secrets to GitHub.
* Use:

```
application-local.properties
```

for local credentials (ignored by Git).

---

## 📌 API Base URL

```
http://localhost:8080/api
```

---

## 👨‍💻 Author

**Akash**
CDAC Project – 2026

---

## 📄 License

This project is for educational purposes.
