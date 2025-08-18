# English Learning Platform

**Full-Stack Web App** designed to help students improve their
English skills while allowing teachers to review student
submissions.  
Built with **Java (Spring Boot)**, **MySQL**, and a responsive frontend
in **HTML, CSS, and JavaScript**.

------------------------------------------------------------------------

## Overview

This platform was developed as a **role-based educational system** where
students can upload materials (texts, audios) and teachers can access
and correct them.
It combines **secure authentication**, **content management**, and an
**interactive placement test** to deliver a complete learning
experience.

------------------------------------------------------------------------

## Key Features
-   🔐 **Authentication System**\
    Secure login and role management (Students / Teachers).

-   👩‍🏫 **Role-based Access**

    -   Students: Upload assignments (text/audio).
    -   Teachers: Access and review student submissions.

-   📖 **Teaching Materials**\
    Songs, texts, and short stories accessible after login (students only).

-   📝 **English Placement Test**\
    30 randomized questions stored in the database with automatic
    scoring.

-   🌍 **Bilingual Interface**\
    Switch between **Spanish** and **English**.

-   🎨 **Modern UI**\
    Custom design with an original background and responsive layout.

------------------------------------------------------------------------

## Tech Stack

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" title="Java" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original-wordmark.svg" alt="HTML5" title="HTML5" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original-wordmark.svg" alt="CSS3" title="CSS3" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" height="28" />
  &nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original.svg" alt="Spring" title="Spring" height="28" />
</p>

-   **Backend:** Java · Spring Boot · JPA
-   **Database:** MySQL
-   **Frontend:** HTML · CSS · JavaScript
-   **Security:** Spring Security (DB-based authentication)

------------------------------------------------------------------------

## Project Structure

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

------------------------------------------------------------------------

## Getting Started

1.  Clone this repository

2.  Configure database in `application.properties`

3.  Run the project with Maven or your IDE (Eclipse/IntelliJ)

4.  Access the app at `http://localhost:8080`


------------------------------------------------------------------------

## Author

**María Ocete**
- 🌐 [Portfolio](https://mariaocete.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/maria-ocete-martin/)
- 💻 [GitHub](https://github.com/MariaOcete)

------------------------------------------------------------------------
