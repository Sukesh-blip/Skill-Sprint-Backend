🛒 ShopNexa – Full Stack Cloud-Native E-Commerce Platform

🔗 Live Demo:
https://salmon-mushroom-072f9aa00.2.azurestaticapps.net/

📌 Overview

ShopNexa is a production-grade, cloud-native e-commerce platform built using Spring Boot, React (Vite), Docker, and Microsoft Azure.

The application demonstrates real-world cloud engineering practices including:

Docker containerization

Azure App Service (Linux container deployment)

Azure Container Registry (ACR)

Azure MySQL Flexible Server

GitHub Actions CI/CD automation

JWT-based authentication with RBAC

Razorpay secure payment integration

This project follows a cloud-first architecture approach and simulates production-level deployment workflows.

🏗 Cloud Architecture
React (Vite SPA)
        ↓
Azure Static Web Apps
        ↓ HTTPS (JWT-secured APIs)
Azure App Service (Dockerized Spring Boot)
        ↓
Azure MySQL Flexible Server
        ↓
Azure Container Registry (Image Storage)
Infrastructure Components

Frontend: Azure Static Web Apps

Backend: Azure App Service (Linux Container)

Container Storage: Azure Container Registry

Database: Azure MySQL Flexible Server

CI/CD: GitHub Actions

Payments: Razorpay (Test Mode)

🔐 Security Features

Stateless JWT Authentication

Role-Based Access Control (ADMIN / USER)

Custom Spring Security authentication filter

Protected Cart, Order & Admin endpoints

Swagger secured using Bearer Token authentication

Production-grade CORS configuration

BCrypt password hashing

💳 Payment Integration (Razorpay)

Integrated Razorpay payment gateway with:

Backend order creation

Secure signature verification

Transaction validation

Payment status handling

User-specific order tracking

Secure callback processing

⚙️ Backend Tech Stack

Java

Spring Boot

Spring Security

Spring Data JPA

Hibernate

MySQL

Docker

🎨 Frontend Tech Stack

React (Vite)

Axios (JWT interceptor)

React Router

Protected Routes

Responsive UI Design

☁️ DevOps & Cloud Deployment
Backend Deployment

Dockerized Spring Boot application

Image pushed to Azure Container Registry

Azure App Service pulls container from ACR

Environment variables configured in Azure

Production logs monitored via Log Stream

Frontend Deployment

React app built via GitHub Actions

Deployed automatically to Azure Static Web Apps

SPA routing configured correctly

Environment variable injection handled at build-time

CI/CD Pipeline

Code pushed to main

GitHub Actions triggered

Docker image built

Image pushed to ACR

App Service pulls latest image

Static Web App rebuilt & deployed

Fully automated deployment workflow.

🧠 Production Engineering Challenges Solved

This project includes real-world debugging experience:

Fixed CORS conflicts between Azure domains

Resolved JWT filter misconfiguration issues

Debugged environment variable injection failures

Fixed Swagger security misalignment

Resolved Hibernate–MySQL schema validation errors

Debugged Docker container cold-start delays

Corrected API routing behavior in Static Web Apps

📸 Deployment Evidence
🔹 Azure Container Registry (ACR)
![image](https://github.com/Sukesh-blip/Skill-Sprint-Backend/blob/f0c9b944e41b8a05731512f6084fca82a1ca1c58/SkillSprint-ACR.png)
🔹 Azure App Service (Backend – Container Based)
![image](https://github.com/Sukesh-blip/Skill-Sprint-Backend/blob/f0c9b944e41b8a05731512f6084fca82a1ca1c58/SkillSprint-App%20service-backend.png)

🔹 Azure MySQL Flexible Server
1[image](https://github.com/Sukesh-blip/Skill-Sprint-Backend/blob/f0c9b944e41b8a05731512f6084fca82a1ca1c58/SkillSprint-AzureMySQL.png)
🔹 GitHub Actions – Successful CI/CD Pipeline
![image](https://github.com/Sukesh-blip/Skill-Sprint-Backend/blob/f0c9b944e41b8a05731512f6084fca82a1ca1c58/SkillSprint-GitHub%20Actions.png)

🔹 Azure Static Web Apps (Frontend)
![image](https://github.com/Sukesh-blip/Skill-Sprint-Backend/blob/f0c9b944e41b8a05731512f6084fca82a1ca1c58/SkillSprint-Static%20web%20apps-Frontend.png)


📂 Core Features

User Registration & Login

Role-Based Admin Panel

Product CRUD (Admin Only)

Add to Cart

Order Placement

Razorpay Secure Payment

Order History Tracking

JWT-secured REST APIs

🏆 Certification & Cloud Alignment

This project demonstrates hands-on implementation aligned with:

Microsoft Azure Fundamentals (AZ-900)

Cloud-native architecture principles

Secure cloud deployment practices

Container-based Azure deployment

DevOps & CI/CD automation

Production debugging & monitoring

👨‍💻 Author

Sukesh Biradar
Software Engineer | Azure Certified (AZ-900)

LinkedIn: https://linkedin.com/in/sukeshbiradar

GitHub: https://github.com/Sukesh-blip

📄 License

This project is built for educational and portfolio demonstration purposes.
