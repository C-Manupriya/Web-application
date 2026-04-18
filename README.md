# EMS-Full-Stack

A full-stack Employee Management System built with Spring Boot (backend) and React (frontend), supporting full CRUD operations on employee records.

# Tech Stack
Backend: Java 17, Spring Boot, Spring Data JPA, MySQL, Lombok
Frontend: React 19, Vite, Axios, Bootstrap 5, React Router DOM

# Features
Create, Read, Update & Delete employee records
RESTful API with clean architecture (DTOs, Services, Repositories)
Responsive UI with Bootstrap
MySQL persistence via JPA/Hibernate
Custom exception handling

# Quick Start
bash
# Backend
cd ems-backend/ems-backend
mvn spring-boot:run        # http://localhost:8080

# Frontend
cd ems-frontend
npm install && npm run dev  # http://localhost:5173

> ⚠️ **Note:** Configure your MySQL credentials in `application.properties` and create the `ems` database before running.
