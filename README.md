# 🏥 Spring Healthcare Management System

A **Spring Boot–based Healthcare Management System** that helps manage doctors, patients, appointments, specializations, documents, and slot requests efficiently.

This project follows **clean layered architecture** using **Spring Boot, Spring Data JPA, Spring Security, Thymeleaf**, and **MySQL**.

---

## 🚀 Features

### 👤 User Management
- User registration & login
- Role-based access (Admin, Doctor, Patient)
- Password generation & update

### 🧑‍⚕️ Doctor Module
- Add, update, view doctors
- Assign specializations
- View appointments

### 🧑‍🤝‍🧑 Patient Module
- Patient registration
- View & manage appointments
- Upload medical documents

### 📅 Appointment Management
- Book appointments
- View appointment history
- Search appointments

### ⏰ Slot Request Management
- Patients request appointment slots
- Doctors approve/reject slots
- Slot status tracking

### 📂 Document Management
- Upload & view documents
- Secure document handling

### 📊 Reports & Export
- Export Specialization data to:
  - PDF
  - Excel

---

## 🛠️ Tech Stack

| Technology | Usage |
|---------|------|
| Java | Core language |
| Spring Boot | Backend framework |
| Spring Data JPA | ORM & DB operations |
| Spring Security | Authentication & Authorization |
| Thymeleaf | UI Templates |
| MySQL | Database |
| Maven | Dependency management |
| Git & GitHub | Version control |

---

## 📁 Project Structure
src/main/java/in/shakthi
├── controller
├── service
│ └── impl
├── repo
├── entity
├── exception
├── config
├── util
├── constants
├── runner
└── view
