# 🎓 University Portal

A full-stack **University Web Portal** developed for project / hackathon purpose.  
The system provides a digital platform for students, faculty, and admin to manage university activities efficiently.

---

## 🚀 Features

- 🏫 University Home Page (Modern UI)
- 👨‍🎓 Student Dashboard
- 👩‍🏫 Faculty Dashboard
- 🔐 Login / Authentication System
- 📚 Course Management
- 📝 Assignment & Test Module
- 📊 Result / Marks View
- 📢 Announcements & Notifications
- 🔎 Search & Filter
- 📱 Responsive Design

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5 / CSS3
- JavaScript
- Axios

### Backend
- Spring Boot
- REST API
- Java

### Database
- MySQL / H2 (configurable)

---


---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Maha070411/up.git
cd up


## 📂 Project Structure
up/
│
├── university-frontend/ # React Frontend Application
│ ├── public/
│ ├── src/
│ │ ├── components/ # Reusable UI Components
│ │ ├── pages/ # Home, Login, Dashboard Pages
│ │ ├── services/ # API Calls (Axios)
│ │ ├── App.js
│ │ └── index.js
│ └── package.json
│
├── university-backend/ # Spring Boot Backend
│ ├── src/main/java/
│ │ ├── controller/ # REST Controllers
│ │ ├── service/ # Business Logic
│ │ ├── repository/ # JPA Repositories
│ │ ├── model/ # Entity Classes
│ │ └── UniversityApplication.java
│ │
│ └── src/main/resources/
│ ├── application.properties
│ └── data.sql (optional)
│
├── pom.xml
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Maha070411/up.git
cd up
2️⃣ Frontend Setup
cd university-frontend
npm install
npm start

Frontend runs at:

http://localhost:3000
3️⃣ Backend Setup

Make sure you have:

Java 17+

Maven

MySQL (if not using H2)

Update application.properties with your database configuration.

Run the backend:

mvn spring-boot:run

Backend runs at:

http://localhost:8080
🔄 API Endpoints (Sample)
Method	Endpoint	Description
GET	/api/students	Get all students
POST	/api/students	Add new student
GET	/api/courses	Get all courses
POST	/api/login	Authenticate user
GET	/api/results	View results
