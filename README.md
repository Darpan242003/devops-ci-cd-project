# devops-ci-cd-project

# 🚀 CI/CD Pipeline for Python Application (GitHub Actions + Docker)

## 📌 Overview
This project demonstrates a complete CI/CD pipeline for a Python-based web application using **GitHub Actions** and **Docker**.

The pipeline automates the process of building, validating, and running the application whenever code is pushed to the repository.

---

## ⚙️ Tech Stack
- Python (FastAPI)
- GitHub Actions (CI/CD)
- Docker (Containerization)
- Linux (Ubuntu environment)

---

## 🔄 CI/CD Pipeline Workflow

The pipeline is triggered on every push to the `main` branch and performs the following steps:

1. **Checkout Code**
2. **Set Up Python Environment**
3. **Install Dependencies**
4. **Run Basic Validation**
5. **Build Docker Image**
6. **Run Container (Deployment Simulation)**

---

## 🐳 Docker Integration
The application is containerized using Docker, ensuring consistency across environments.

---

## 🖥️ Running Locally

```bash
git clone <repo-url>
cd project-folder
docker build -t ci-cd-app .
docker run -p 8000:8000 ci-cd-app