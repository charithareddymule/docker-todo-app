# 🚀 Dockerized Node.js Web Application

## 🌐 Live Application

👉 **Open in your browser:**

### 🔗 http://localhost:8080

[![Open App](https://img.shields.io/badge/Open-App-blue?style=for-the-badge)](http://localhost:8080)

---

## 📌 Project Overview

This project demonstrates how to containerize a simple Node.js application using Docker and run it locally.

* Built a basic Node.js web server using Express
* Created a Dockerfile to define the container environment
* Built a Docker image and ran it as a container
* Exposed the application on port **8080**
* Verified the application through a web browser

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* Docker
* Git & GitHub

---

## 📂 Project Structure

```
docker-todo-app/
│
├── package.json
├── server.js
├── Dockerfile
├── .dockerignore
└── README.md
```

---

## ⚙️ How to Run This Project

### 1️⃣ Clone the repository

```
git clone https://github.com/YOUR_USERNAME/docker-todo-app.git
cd docker-todo-app
```

---

### 2️⃣ Build Docker Image

```
docker build -t todo-app .
```

---

### 3️⃣ Run Docker Container

```
docker run -p 8080:8080 -d todo-app
```

---

## 🎯 Output

The application will display:

👉 **Hello from Docker App 🚀**

---

## 📸 Screenshots

(Add your screenshots here)

---

## 💡 Key Learnings

* Understanding Dockerfile instructions
* Containerizing applications
* Managing dependencies inside containers
* Running and exposing containerized apps

---

## 🔗 Author

**Charitha Reddy**

---

## ⭐ Acknowledgment

This project was completed as part of the **IBM Cloud Fundamentals Certification**.
