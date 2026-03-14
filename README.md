# 🚀 End-to-End CI/CD Pipeline using Jenkins & Docker

This project demonstrates a complete CI/CD pipeline implementation using Jenkins and Docker.  
The pipeline automatically builds a Docker image from application code and deploys it as a container.

---

## 🛠 Tools & Technologies

- GitHub – Source Code Management
- Jenkins – Continuous Integration & Continuous Deployment
- Docker – Containerization
- Docker Hub – Image Repository
- Nginx – Web Server

---

## ⚙️ CI/CD Pipeline Workflow

1. Developer pushes code to GitHub repository
2. Jenkins pipeline automatically triggers the build
3. Docker image is created from the application code
4. Image is pushed to Docker Hub
5. Docker container is deployed and the application runs

---

## 📦 Docker Commands Used

Build Image

docker build -t devops-app .

Run Container

docker run -d -p 8081:80 devops-app

---

## 🌐 Application Access

http://localhost:8081

---

## 📂 Project Structure

devops-demo-app
│
├── Dockerfile
├── Jenkinsfile
├── index.html
└── README.md

---

## 🏗 CI/CD Architecture

Developer pushes code to GitHub repository → Jenkins pipeline is triggered → Docker image is built → Docker container is deployed and application runs.

GitHub → Jenkins → Docker Build → Docker Container → Application

---

## 📌 Project Outcome

- Automated CI/CD pipeline using Jenkins
- Containerized application deployment using Docker
- Hands-on experience with DevOps tools

---

## 👩‍💻 Author

Aiswaryaroy S  
DevOps Engineer
