# 🐳 Two-Tier Flask Application

<div align="center">

<h2>Flask + MySQL with Docker Compose</h2>

<p>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/Architecture-Two--Tier-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Made_for-Learning-orange?style=flat-square" />
</p>

</div>

---

## 📌 About

A simple **two-tier web application** built using **Flask** and **MySQL**, containerized with **Docker** and orchestrated using **Docker Compose**.

The application demonstrates communication between an application container and a database container, providing a practical example of a two-tier architecture. This project is designed to showcase containerization, service networking, and database integration using Docker.

---

## 📁 Project Structure

```text
.
├── Dockerfile
├── README.md
├── app.py
├── docker-compose.yml
├── message.sql
├── requirements.txt
└── templates
    └── index.html
```

---

## 🧩 Components

### 🌐 Flask Application

The Flask application serves the web interface and handles interactions with the MySQL database.

### 🗄️ MySQL Database

MySQL is used as the backend database for storing and retrieving application data.

### 🐳 Docker

A Dockerfile is used to package the Flask application into a portable container image.

### ⚙️ Docker Compose

Docker Compose simplifies the deployment process by managing both the Flask and MySQL services through a single configuration file.

---

## ✨ Features

- 🌐 Flask-based web application
- 🗄️ MySQL database integration
- 🐳 Dockerized application environment
- ⚙️ Multi-container deployment with Docker Compose
- 🔗 Service-to-service communication using Docker networking

---

## ✅ Prerequisites

Make sure the following tools are installed:

- 🐳 Docker
- ⚙️ Docker Compose

---

## 🚀 Getting Started

### 🔨 Build and Start Services

```bash
docker compose up --build
```

### ▶️ Run in Detached Mode

```bash
docker compose up -d
```

### ⏹️ Stop Services

```bash
docker compose down
```

---

## 🌍 Application Access

Once the services are running, the application can be accessed through:

```text
http://localhost:5000
```

---

## 🎯 Learning Objectives

This project demonstrates:

- 🏗️ Building Docker images
- 📦 Running multi-container applications
- 🔗 Container networking
- 🗄️ Database connectivity
- ⚙️ Docker Compose workflows
- 🧱 Two-tier application architecture

---

## 📜 License

This project is licensed under the terms specified in the repository license.

---

<div align="center">

### 🚀 Happy Dockerizing!

<img src="https://img.shields.io/badge/Flask-MySQL_Docker_App-success?style=for-the-badge&logo=docker&logoColor=white" />

</div>