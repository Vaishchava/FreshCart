# 🛒 FreshCart - DevOps Deployment & Automation

This repository contains my **DevOps implementation** for the FreshCart e-commerce application. The original project has been forked, and my focus is on deploying and automating the application using modern DevOps practices.

## 📌 About This Project

The goal of this project is to gain hands-on experience with real-world DevOps workflows by taking an existing application and implementing:

* Docker containerization
* Multi-container deployment with Docker Compose
* AWS EC2 deployment
* Infrastructure as Code (Terraform)
* CI/CD using GitHub Actions
* Production-style deployment automation

This project is part of my DevOps learning journey and portfolio.

---

## 🚀 DevOps Technologies

* Linux (Ubuntu)
* Git & GitHub
* Docker
* Docker Compose
* AWS EC2
* Terraform
* GitHub Actions
* Docker Hub

---

## 📂 Project Structure

```text
FreshCart/
├── client/
│   ├── Dockerfile
│   └── ...
├── server/
│   ├── Dockerfile
│   └── ...
├── docker-compose.yml
├── terraform/
│   └── ...
└── .github/
    └── workflows/
        └── ci-cd.yml
```

---

## ⚙️ Features Implemented

* Dockerized frontend
* Dockerized backend
* Multi-container setup using Docker Compose
* Automated Docker image builds
* Docker Hub image publishing
* Automated deployment to AWS EC2
* Infrastructure provisioning using Terraform
* GitHub Actions CI/CD pipeline

---

## 🔄 CI/CD Workflow

```text
Developer
    │
git push
    │
    ▼
GitHub Actions
    │
    ▼
Build Docker Images
    │
    ▼
Push Images to Docker Hub
    │
    ▼
SSH into AWS EC2
    │
    ▼
docker compose pull
    │
    ▼
docker compose up -d
```

---

## 🛠️ Deployment

The application is deployed on an AWS EC2 instance using Docker Compose.

Deployment process:

1. Push code to the `main` branch.
2. GitHub Actions builds the Docker images.
3. Images are pushed to Docker Hub.
4. GitHub Actions connects to the EC2 instance over SSH.
5. The server pulls the latest images.
6. Docker Compose updates the running containers automatically.

---

## 📚 Learning Objectives

This project helped me understand:

* Docker image creation
* Multi-container applications
* Docker networking
* Docker Compose
* AWS EC2 deployment
* Infrastructure as Code with Terraform
* CI/CD automation using GitHub Actions
* Production deployment workflow

---

## 🔮 Future Improvements

* Kubernetes deployment
* Nginx reverse proxy
* HTTPS with Let's Encrypt
* Monitoring using Prometheus & Grafana
* Blue-Green deployments
* Image versioning
* Automated rollback strategy

---

## 🙏 Credits

The original FreshCart application was developed by:

### Mihir Parekh

* GitHub: https://github.com/Mihir-3
* LinkedIn: https://www.linkedin.com/in/parekh-mihir

### Makadia Deep

* GitHub: https://github.com/makadia-deep
* LinkedIn: https://www.linkedin.com/in/deep-makadia-dev

This repository focuses on the **DevOps implementation, deployment, and automation** of the original application.

---

## 👨‍💻 DevOps Implementation

**Vaishnav Chavan**

* GitHub: https://github.com/Vaishchava
* LinkedIn: https://www.linkedin.com/in/vaishnav-chavan-4a518a175

I'm currently building hands-on DevOps projects covering Linux, Docker, AWS, Terraform, GitHub Actions, Kubernetes, and CI/CD as part of my journey toward becoming a DevOps Engineer.
