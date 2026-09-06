# Docker Compose WordPress CI/CD with Self-Hosted GitHub Actions Runner

A complete **DevOps CI/CD project for deploying WordPress using Docker Compose and GitHub Actions with a self-hosted runner on AWS EC2**.

This project demonstrates how to containerize a WordPress application with MySQL, automate deployment using GitHub Actions, and execute CI/CD workflows through a **self-hosted GitHub Actions runner** running on an EC2 instance.

## 🚀 Project Overview

The application consists of:

* **WordPress** – Web application
* **MySQL** – WordPress database
* **Docker & Docker Compose** – Containerization and application orchestration
* **GitHub Actions** – CI/CD automation
* **Self-Hosted Runner** – Executes GitHub Actions workflows directly on an AWS EC2 server
* **AWS EC2** – Hosting environment
* **Git/GitHub** – Source code management and version control

### 🔄 CI/CD Workflow

```text
Developer
    │
    │ git push
    ▼
GitHub Repository
    │
    │ GitHub Actions
    ▼
Self-Hosted Runner
    │
    │ Docker Compose
    ▼
Docker Containers
    ├── WordPress
    └── MySQL
    │
    ▼
Running WordPress Application
```

## 🛠️ Technologies Used

* AWS EC2
* Amazon Linux
* Docker
* Docker Compose
* WordPress
* MySQL
* Git
* GitHub
* GitHub Actions
* Self-Hosted GitHub Actions Runner
* Linux/Bash

## 📌 Key Features

* Containerized WordPress application
* MySQL database running in a separate container
* Docker Compose for multi-container orchestration
* Automated CI/CD pipeline using GitHub Actions
* Self-hosted GitHub Actions runner on AWS EC2
* Automatic deployment after pushing changes to GitHub
* Persistent Docker volumes for WordPress and MySQL data
* Infrastructure suitable for learning real-world DevOps deployment practices

## 🎯 Purpose

The main purpose of this project is to understand and demonstrate a practical **DevOps CI/CD workflow**, from source-code changes to automated deployment.

It provides hands-on experience with:

1. Git and GitHub
2. Docker containerization
3. Docker Compose
4. AWS EC2
5. GitHub Actions
6. Self-hosted runners
7. Automated application deployment
8. Linux server administration

## 👨‍💻 Learning Outcome

By completing this project, you can gain practical experience in building a simple CI/CD pipeline where a developer pushes code to GitHub and the application is automatically deployed to an AWS EC2 server using Docker Compose.

This project can also serve as a foundation for more advanced DevOps practices such as **Docker image registries, reverse proxies, HTTPS, monitoring, secrets management, Terraform, Kubernetes, and production-grade CI/CD pipelines**.
