# Infinite Loop – CI/CD Deployment to AWS ECS Fargate

This project demonstrates a **fully automated CI/CD pipeline** for a containerized frontend application using **GitHub Actions**, **Amazon ECR**, and **Amazon ECS Fargate** behind an **Application Load Balancer (ALB)**.

The application used is the **Infinite Loop** static HTML template from Tooplate, served using **Nginx** in a Docker container.

---

## 🚀 Architecture Overview

GitHub → GitHub Actions  
→ Docker Build  
→ Amazon ECR  
→ Amazon ECS (Fargate)  
→ Application Load Balancer  
→ Users

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Tooplate Infinite Loop)
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Container Registry:** Amazon ECR
- **Orchestration:** Amazon ECS (Fargate)
- **Load Balancing:** Application Load Balancer
- **Cloud Provider:** AWS

---

## 📂 Project Structure

```text
.
├── css/
├── img/
├── js/
├── index.html
├── Dockerfile
├── task-definition.json
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
