# Hi, I'm Sushanth Koyalakonda 👋

#### B.Tech Mathematics & Computing
Manipal Institute of Technology, Manipal

---

I'm a fourth-year B.Tech student, focused on building reliable backend systems and preparing for Software Engineering / SDE roles.

I enjoy working with APIs, databases, real-time communication, asynchronous processing, caching, and scalable backend architecture.

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sushanth-koyalakonda-34ba69328/)
[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sushkk12@gmail.com)

---

## Skills

### Languages

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & Web

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Databases & Caching

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps & Tools

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## Projects

### Real-Time Chat Platform with AI Summarization

Real-time messaging platform with WebSockets, PostgreSQL persistence, Redis-backed asynchronous processing, and AI-powered conversation summarization.

- Load-tested with **500 concurrent WebSocket connections**, achieving **46.8 msg/s throughput** and **139.22 ms p95 latency**
- Reduced client-perceived AI summarization latency by **99.6%** using an asynchronous BullMQ + Redis pipeline
- Implemented JWT authentication, RBAC, Redis-backed sessions, and Docker Compose deployment

**Tech:** `Node.js` `Express` `PostgreSQL` `Redis` `BullMQ` `WebSockets` `Docker`

---

### Single-Shop E-commerce Platform

Full-stack e-commerce platform with role-based authorization, transactional order processing, and support for both relational and document-oriented databases.

- Implemented Customer, Admin, and Owner roles with Passport.js and custom authorization middleware
- Built equivalent **MongoDB and MySQL** data models and ACID-compliant order processing
- Prevented overselling through transactional stock updates and row-level locking

**Tech:** `Node.js` `Express.js` `MongoDB` `MySQL` `Passport.js`

---

### Stream-Based File Processing CLI

Node.js command-line tool for processing large CSV and JSON datasets using streaming and Worker Threads.

- Processes **500MB+ files using approximately 12MB memory**
- Achieved approximately **97% lower memory usage** compared with in-memory processing
- Uses Worker Threads for CPU-intensive workloads while keeping the main event loop responsive

**Tech:** `Node.js` `Streams` `Worker Threads` `Commander.js`

---
