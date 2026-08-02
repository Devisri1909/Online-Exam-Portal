# 📝 Online Examination System

An Online Examination System built using **Spring Boot** that enables administrators to manage examinations and students to attend exams securely through a web interface. The application provides role-based authentication, automated evaluation, and instant result generation.

---

## 🚀 Overview

Traditional paper-based examinations require significant manual effort for creating question papers, conducting exams, and evaluating answer sheets. This project digitizes the entire examination process by providing a secure and efficient web-based platform.

The system supports two user roles:

- **Administrator** – Creates and manages exams, questions, and student records.
- **Student** – Registers, logs in securely, attends examinations, and views results.

---

## 🌟 Major Features

### Administrator

- Authentication using Spring Security
- Create and manage examinations
- Add, edit, and delete questions
- Monitor registered students
- View examination results
- Manage user accounts

### Student

- New user registration
- Secure login
- View available exams
- Attempt online examinations
- Automatic answer evaluation
- Instant score display
- View examination history
- Update profile details

---

# 🛠 Tech Stack

### Backend

- Java 17
- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Hibernate

### Frontend

- Thymeleaf
- HTML5
- CSS3
- Bootstrap 5
- JavaScript

### Database

- H2 Database

### Build Tool

- Maven

---

# 🏗 Architecture

```
Presentation Layer
        │
Thymeleaf Templates
        │
Spring MVC Controllers
        │
Business Logic (Services)
        │
Spring Data JPA
        │
H2 Database
```

---

# 📁 Project Structure

```
online-exam-system
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── config
│   │   │   ├── controller
│   │   │   ├── model
│   │   │   ├── repository
│   │   │   ├── service
│   │   │   └── OnlineExamApplication.java
│   │   │
│   │   ├── resources
│   │   │   ├── static
│   │   │   ├── templates
│   │   │   └── application.properties
│   │
│   └── test
│
├── data
├── uploads
├── pom.xml
└── README.md
```

---

# ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/online-exam-system.git
```

### Move into Project Folder

```bash
cd online-exam-system
```

### Run the Application

Windows

```bash
mvnw.cmd spring-boot:run
```

Linux / macOS

```bash
./mvnw spring-boot:run
```

---

# 🌐 Access Application

```
http://localhost:7890
```

---

# 🗄 Database

### H2 Console

```
http://localhost:7890/h2-console
```

### JDBC URL

```
jdbc:h2:file:./data/examdb
```

### Username

```
sa
```

### Password

```
password
```

---

# 🔒 Authentication

The application uses **Spring Security** with **BCrypt Password Encryption**.

Two user roles are supported:

- ADMIN
- STUDENT

Access permissions are enforced using role-based authorization.

---

# 📊 Functional Workflow

```
Student Registration
        ↓
Student Login
        ↓
Available Exams
        ↓
Take Examination
        ↓
Automatic Evaluation
        ↓
Score & Result
```

---

# 💡 Highlights

- Responsive User Interface
- Secure Authentication
- Role-Based Authorization
- Automatic Result Calculation
- Exam & Question Management
- Persistent Database Storage
- MVC Architecture
- Clean Code Structure

---

# 🔮 Future Improvements

- Email Verification
- Password Recovery
- JWT Authentication
- MySQL/PostgreSQL Support
- Random Question Generation
- Negative Marking
- Leaderboard
- PDF Result Download
- Email Notifications
- Online Proctoring using Webcam

---

# 📸 Screenshots

Add screenshots of:

- Home Page
- Login Page
- Registration Page
- Admin Dashboard
- Student Dashboard
- Exam Page
- Question Management
- Result Page

---

# 👨‍💻 Developed By

**Devi Sri Amrutha Avidi**

B.Tech – Computer Science and Engineering

**GitHub:** https://github.com/your-github-username

**LinkedIn:** https://linkedin.com/in/your-linkedin-profile

---

# 📜 License

This project is developed for educational and learning purposes.