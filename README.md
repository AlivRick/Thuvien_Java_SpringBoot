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

  ![Homepage](https://github.com/user-attachments/assets/a19c7856-f9cc-4a56-a8df-cab2f86f86a9)


- **Book Search:**

  ![Book Search](https://github.com/user-attachments/assets/c1a38e48-ef7c-4e92-b40d-276fd7f08a52)


- **Borrow Book:**

  ![Borrow Book](https://github.com/user-attachments/assets/ba24575e-5249-4df6-9782-0bcf7d769919)


- **User Profile:**

  ![User Profile](https://github.com/user-attachments/assets/31c6b1fd-fc56-48d9-95dc-ddca0ad61fa6)


- **Admin Dashboard:**

  ![Admin Dashboard](https://github.com/user-attachments/assets/ea02230c-f2aa-4348-a894-4905b35bba59)
- **Payment online:**

![z5944806690874_cf44348cca191b048337e3b4f3d3a4e4](https://github.com/user-attachments/assets/e42bddd1-0b70-42f4-851e-9c55d17086ab)
![z5944808480859_0fd76a138c4e76409a459a3cde68684c](https://github.com/user-attachments/assets/391fea4a-3832-4a35-9efc-95e3c5ffb2f5)
![z5944809857253_bee24f6b0450006a46d0ed930beb2e56](https://github.com/user-attachments/assets/ccd43ef4-96f7-4ba2-b407-045ed579ad90)


---

## Credits

- **[Hoàng Châu Phúc Thuận]** - Fullstack Developer
- **[Trần Hoài Nam]** - Fullstack Developer
- **[Nguyễn Quốc Cường]** - Frontend Developer

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
