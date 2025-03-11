# 🚀 Job Portal Web Application (MERN + TypeScript)

A modern, scalable job portal platform with three user roles: Admin, User, and Company. Users can apply for jobs, interact socially (posts, comments, likes, messaging), and manage profiles. Companies can post jobs, manage their company profiles, and view applicant data. Admins oversee the entire platform with full management capabilities.

## 📚 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Architecture](#-architecture)

## ✨ Features

### 👤 User Role

- Register & Login with JWT authentication
- Create, edit, and manage profile
- View profile viewers (subscription feature)
- Create, edit, and delete posts with comments and likes
- Apply to jobs (unlimited applications with subscription)
- Send & receive real-time messages (chat) via Socket.IO
- Receive real-time notifications
- Subscription plans for enhanced features(including resume generation)
- Generate and download professional resumes

### 🏢 Company Role

- Register & Login as a company
- Create, edit, and delete job
- Create, edit, and delete post
- Like and comment to posts
- Manage company profile
- View applicants and their profiles

### 🛠️ Admin Role

- Manage Users
- Manage Companies
- Manage Jobs
- Complete platform moderation (approve, delete users/companies/jobs)
- Analytics and reports

## 💻 Tech Stack

### Frontend

- Next.js (React framework)
- Bootstrap (UI styling)
- TypeScript (strict typing & scalability)
- Socket.IO Client (real-time messaging & notifications)

### Backend

- Node.js
- Express.js
- MongoDB (NoSQL Database)
- Mongoose (ODM)
- TypeScript
- JWT (JSON Web Token) for authentication
- Socket.IO Server (real-time communication)
- Repository Pattern (clean, maintainable code structure)
- RESTful APIs

### Tools & DevOps

- Git & GitHub
- Postman (API testing)
- VS Code
- Cloud Deployment (optional)

## 🏗️ Architecture

Clean, scalable backend architecture using:

- MERN Stack + TypeScript
- Repository Pattern
- Real-time Communication (WebSockets via Socket.IO)
