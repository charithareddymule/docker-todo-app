# 🚀 Dockerized Node.js Web Application

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
<img width="1918" height="1145" alt="Screenshot 2026-04-25 114951" src="https://github.com/user-attachments/assets/e610aa22-1658-4015-8346-5380f6535f37" />
<img width="1635" height="885" alt="Screenshot 2026-04-25 115147" src="https://github.com/user-attachments/assets/c82f1dc1-cc47-4d91-98be-cb211ea564b6" />
<img width="999" height="1154" alt="Screenshot 2026-04-25 115236" src="https://github.com/user-attachments/assets/146b68c0-e091-41b8-9c6a-838a3b3f0bbf" />
<img width="1917" height="1149" alt="Screenshot 2026-04-25 115412" src="https://github.com/user-attachments/assets/1c5f6073-bf7f-4c8b-a0a6-984d62519655" />


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
