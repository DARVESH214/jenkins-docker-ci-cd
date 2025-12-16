# Jenkins CI/CD Pipeline with Docker

## 📌 Project Overview
This project demonstrates a simple end-to-end CI/CD pipeline using **Jenkins** and **Docker** on an AWS EC2 instance.

The pipeline automatically:
- Builds a Docker image
- Runs a Docker container
- Deploys a sample HTML application

---

## ❓ Why did I build this project?<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0bd4bdb8-560d-4fd1-bbc5-a73d34132ac2" />

I built this project to understand **how CI/CD works in real DevOps environments**, not just in theory.

My goals:
- Learn Jenkins pipeline basics
- Understand Docker build & run automation
- Gain hands-on experience with real errors and fixes
- Practice DevOps tools integration

---

## 🛠 Tools Used
- Jenkins (CI/CD automation)
- Docker (containerization)
- GitHub (source code management)
- AWS EC2 (infrastructure)

---

## ⚙️ Why Jenkins?
Jenkins is used because:
- It automates build and deployment tasks
- It supports pipelines as code (Jenkinsfile)
- It integrates easily with GitHub and Docker

👉 Jenkins removes manual work and reduces human errors.

---

## 🐳 Why Docker?
Docker is used because:
- It packages the application with all dependencies
- It ensures the application runs the same everywhere
- It allows fast deployment using containers

👉 Docker solves the "it works on my machine" problem.

---

## 🤔 Why Jenkins + Docker together?
Using Jenkins with Docker allows:
- Fully automated CI/CD pipelines
- Faster and reliable deployments
- Easy rollback and consistency

This combination is widely used in real-world DevOps projects.

---

## ❌ When NOT to use this approach?
This setup is **not ideal** when:
- The project is very small and does not need automation
- There is no need for frequent deployments
- Docker is not allowed due to security or compliance restrictions

---

## 🚀 What did I learn?
- Jenkins pipeline creation and execution
- Docker image build and container management
- GitHub authentication using Personal Access Tokens
- Debugging real CI/CD issues

---

## 📂 Project Structure
