# 🔐 Secure Notes Application

A secure, scalable, and full-stack web application designed to store and manage personal notes safely.  
This project focuses on **modern authentication, authorization, and security best practices** using Spring Boot on the backend and React on the frontend.

---

## 📌 Project Overview

The Secure Notes Application allows users to create, manage, and store notes securely.  
It implements **enterprise-level security features** such as JWT authentication, OAuth2 login, Multi-Factor Authentication, role-based authorization, and CSRF protection.

This project is ideal for demonstrating **real-world backend security concepts** and **full-stack development skills**.

---

## 🚀 Features

### 🔑 Authentication & Authorization
- User **Sign Up** and **Sign In**
- **JWT-based Authentication** for secure stateless sessions
- **Role-Based Authorization** (USER / ADMIN)
- **OAuth2 Authentication** (third-party login)
- **Multi-Factor Authentication (MFA)** for enhanced security

### 🔐 Security
- Encrypted password storage
- **Custom Security Filters**
- **CSRF Protection**
- Secure environment variable management
- Protected APIs with Spring Security

### 🧾 Admin Features
- **Admin Auditing**
- User activity monitoring
- Role-based access control

### 📧 Email Services
- Email verification during registration
- Secure account activation

### 🎨 Frontend
- Built with **React**
- Styled using **Tailwind CSS**
- Responsive and clean UI

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- JWT
- OAuth2
- REST APIs

### Security
- JWT Authentication
- OAuth2

### Tools & Others
- Maven
- Git & GitHub

---

## 📂 Project Structure
Live-Chat-Application
│
├── src/main/java/com/chat/app
│ ├── AppApplication.java
│ ├── config
│ │ └── WebSocketConfig.java
│ ├── controller
│ │ └── ChatController.java
│ └── model
│ └── ChatMessage.java
│
├── src/main/resources
│ ├── application.properties
│ └── templates
│ └── chat.html
│
├── src/test/java/com/chat/app
│ └── AppApplicationTests.java
│
├── pom.xml
├── README.md
└── mvnw


---

## ⚙️ How to Run the Project

### 🔹 Prerequisites
- Java 8 or above
- Maven
- Any IDE (IntelliJ / Eclipse / STS)

---

### 🔹 Steps to Run

1. Clone the repository
   ```bash
   git clone https://github.com/Isha160/Live-Chat-Application.git
   ~~~
2- Navigate to the project directory

```cd Live-Chat-Application~~~

3- Run the application

```mvn spring-boot:run~~~

4- Open the browser and visit

```http://localhost:8080/chat~~~
