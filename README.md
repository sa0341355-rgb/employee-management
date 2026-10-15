# Employee Management System

---

## 🚀 Features

### 🔐 Authentication & Authorization
- JWT-based authentication
- Role-based access control:
  - **ADMIN** → Full access (Create, Update, Delete)
  - **USER** → Read-only access

### 👨‍💼 Employee Management
- Add new employees (Admin only)
- Update employee details (Admin only)
- Delete employees (Admin only)
- View employee list (Admin & User)
- Pagination, sorting, and search


### 🛠 Backend
- Spring Boot
- Spring Security
- JWT Authentication Filter
- JPA + Hibernate
- MySQL Database
- Validation with Hibernate Validator

---

## 🧰 Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Security
- JWT (jjwt)
- JPA / Hibernate
- MySQL
- Maven

---

## ⚙️ Setup Instructions

### 1️⃣ Backend Setup (Spring Boot)

```bash
cd employee-backend
mvn clean install
mvn spring-boot:run
```

