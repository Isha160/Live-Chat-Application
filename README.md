

## 📌 Project Description

Live Chat Application is a real-time web application developed using Spring Boot and WebSockets that enables users to communicate instantly through a browser-based interface. The application uses the WebSocket protocol with STOMP messaging to establish a persistent, bidirectional connection between client and server, ensuring low-latency message delivery without page refresh.
---

<pre>
Live-Chat-Application
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── chat
│   │   │           └── app
│   │   │               ├── AppApplication.java
│   │   │               ├── config
│   │   │               │   └── WebSocketConfig.java
│   │   │               ├── controller
│   │   │               │   └── ChatController.java
│   │   │               └── model
│   │   │                   └── ChatMessage.java
│   │   │
│   │   └── resources
│   │       ├── application.properties
│   │       └── templates
│   │           └── chat.html
│   │
│   └── test
│       └── java
│           └── com
│               └── chat
│                   └── app
│                       └── AppApplicationTests.java
│
├── pom.xml
├── README.md
└── mvnw
</pre>

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
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── chat
│   │   │           └── app
│   │   │               ├── AppApplication.java
│   │   │               ├── config
│   │   │               │   └── WebSocketConfig.java
│   │   │               ├── controller
│   │   │               │   └── ChatController.java
│   │   │               └── model
│   │   │                   └── ChatMessage.java
│   │   │
│   │   └── resources
│   │       ├── application.properties
│   │       └── templates
│   │           └── chat.html
│   │
│   └── test
│       └── java
│           └── com
│               └── chat
│                   └── app
│                       └── AppApplicationTests.java
│
├── pom.xml
├── README.md
└── mvnw



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

2- Navigate to the project directory

```bash
cd Live-Chat-Application

3- Run the application

```bash
mvn spring-boot: run

4- Open the browser and visit

```bash
http://localhost:8080/chat

## 🔁 WebSocket Flow

- Client connects to the WebSocket endpoint  
- Messages are sent using **STOMP protocol**  
- Server processes messages via WebSocket controller  
- Messages are broadcast to all subscribed clients in real time

## ✅ Conclusion

This Live Chat Application successfully demonstrates real-time communication using Spring Boot and WebSockets. The project reflects a strong understanding of backend development concepts, event-driven architecture, and persistent client–server connections. It showcases practical experience in building scalable, secure, and responsive web applications, making it a solid foundation for real-world chat systems and modern web solutions.
