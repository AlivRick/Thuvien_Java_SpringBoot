# **Library Management System**

## Description

This **Library Management System** is a full-stack web application designed to facilitate online book borrowing and management. Built with **Spring Boot** for the backend and **Thymeleaf** for the frontend, the system allows users to browse books, borrow them, renew loans, and manage their library accounts seamlessly.

- **Motivation:** The motivation for creating this project stemmed from the need for a streamlined platform to manage library transactions and improve user experience.
- **Why was this built?** This project was developed to provide an efficient solution for library management, addressing challenges like tracking borrowed books, managing member accounts, and automating overdue fines.
- **Problem it solves:** It tackles issues such as complex book borrowing processes, unorganized member management, and ineffective communication between library staff and users.
- **What did I learn?** Through this project, I learned how to integrate **Spring Data JPA** for database operations, implement security with **Spring Security**, handle payment systems, and create a user-friendly frontend with **Thymeleaf**.

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Features](#features)

---

## Installation

### Backend (Spring Boot)

#### Prerequisites
- Java 11 or higher
- Maven

#### Steps
1. Clone the repository from GitHub and open the backend folder in your preferred IDE.
2. Ensure that Java and Maven are correctly configured.
3. Build and run the Spring Boot application to start the backend server.

### Frontend (Thymeleaf)

#### Prerequisites
- No additional prerequisites; Thymeleaf is integrated within the Spring Boot application.

#### Steps
1. The frontend is served directly from the Spring Boot application. Ensure the backend is running.
2. Access the application through your browser.

---

## Usage

Once the backend server is running, navigate to `http://localhost:8080` in your browser. Below are some screenshots showcasing key features:

- **Homepage:**

  ![Homepage](uploads/1.png)

- **Book Search:**

  ![Book Search](uploads/2.png)

- **Borrow Book:**

  ![Borrow Book](uploads/3.png)

- **User Profile:**

  ![User Profile](uploads/4.png)

- **Admin Dashboard:**

  ![Admin Dashboard](uploads/5.png)

---

## Credits

- **[Your Name]** - Fullstack Developer
- **[Team Member 1]** - Backend Developer
- **[Team Member 2]** - Frontend Developer

---

## Features
- User authentication and role-based access control using **Spring Security**
- CRUD operations for managing books and users
- Book borrowing and renewal functionalities
- Payment integration via **VNPay** for membership and fines
- Email verification and password reset through **SMTP**
- Search functionality with multi-criteria filtering
- Responsive design using **Thymeleaf**
- Admin panel for managing library operations and reporting
