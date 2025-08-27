# English Learning Platform

**Full-Stack Web App** designed to help students improve their
English skills while allowing teachers to review student
submissions.  
Built with **Java (Spring Boot)**, **MySQL**, and a responsive frontend
in **HTML, CSS, and JavaScript**.

---

## 🚀 Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-17-orange?logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-3.4.4-brightgreen?logo=springboot" />
  <img src="https://img.shields.io/badge/MySQL-8.0-blue?logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black" />
</p>

- **Backend:** Java · Spring Boot · JPA  
- **Database:** MySQL  
- **Frontend:** HTML · CSS · JavaScript  
- **Security:** Spring Security (DB-based authentication)  

---

## 📖 Overview

This platform was developed as a **role-based educational system** where
students can upload materials (texts, audios) and teachers can access
and correct them.  
It combines **secure authentication**, **content management**, and an
**interactive placement test** to deliver a complete learning
experience.

---

## ✨ Key Features

- 🔐 **Authentication System**  
  Secure login and role management (Students / Teachers).

- 👩‍🏫 **Role-based Access**
  - Students: Upload assignments (text/audio).
  - Teachers: Access and review student submissions.

- 📖 **Teaching Materials**  
  Songs, texts, and short stories accessible after login (students only).

- 📝 **English Placement Test**  
  30 randomized questions stored in the database with automatic
  scoring.

- 🌍 **Bilingual Interface**  
  Switch between **Spanish** and **English**.

- 🎨 **Modern UI**  
  Custom design with an original background and responsive layout.

---

## 📂 Project Structure

```
src/
 ├── main/java/com.englishweb/
 │   ├── controller/   # Controllers
 │   ├── model/        # Entities
 │   ├── repository/   # Repositories
 │   ├── service/      # Business logic
 │   └── security/     # Spring Security config
 └── resources/
     ├── static/       # HTML, CSS, JS
     └── application.properties
```

---

## 🛠️ Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/MariaOcete/english-web.git
   cd english-web
   ```

2. Configure your database in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://127.0.0.1:3306/english_web
   spring.datasource.username=englishuser
   spring.datasource.password=EngWeb-2025!Ok
   ```

3. Run the project with Maven:
   ```bash
   ./mvnw clean spring-boot:run
   ```

4. Access the app at:  
   👉 [http://localhost:8080](http://localhost:8080)

---

## 📸 Screenshots

### 🏠 Home Page (Improving design)
<img src="https://github.com/user-attachments/assets/1c017325-c42b-4c5d-8750-b3bd1e747f0d" width="800"/>

### 📝 Placement Test
<img src="https://github.com/user-attachments/assets/a03da545-de6c-4d8c-a5e2-95cbb6eefe3c" width="800"/>
<img src="https://github.com/user-attachments/assets/79e6f149-79ff-4bec-86ae-d27da70e3d35" width="800"/>

### 🎓 Student Dashboard
<img src="https://github.com/user-attachments/assets/5c8917d2-47b9-428f-a0c3-1071d1adc761" width="800"/>

### 👩‍🏫 Teacher Dashboard
<img src="https://github.com/user-attachments/assets/87abf51c-5b87-43e7-89a7-6350f717b69c" width="800"/>

---

## 🔮 Future Improvements

- 🔄 Dockerize the app (Spring Boot + MySQL).  
- 🎨 Replace static HTML with React or Angular frontend.  
- 📊 Add teacher dashboards with statistics.  
- ✅ Add unit & integration tests.  
- ☁️ Deploy to cloud (Render / AWS / Heroku).  

---

## 👩‍💻 Author

**María Ocete**  
🌐 [Portfolio](https://mariaocete.com) · 💼 [LinkedIn](https://www.linkedin.com/in/maria-ocete-martin/) · 💻 [GitHub](https://github.com/MariaOcete)
