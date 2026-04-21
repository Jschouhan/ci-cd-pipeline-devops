# 🚀 CI/CD Pipeline using GitHub Actions, Jenkins & Docker

## 📌 Overview
This project demonstrates a complete CI/CD pipeline that automates the process of building, testing, and deploying an application using modern DevOps tools.

## ❓ Problem
Manual deployment is slow, error-prone, and inefficient. Teams need an automated pipeline to ensure faster and reliable releases.

## 💡 Solution
Built a CI/CD pipeline using:
- GitHub Actions for Continuous Integration
- Jenkins for Continuous Deployment
- Docker for containerization

## 🛠️ Tech Stack
- GitHub Actions
- Jenkins
- Docker
- Node.js
- Linux

## ⚙️ Pipeline Workflow
1. Developer pushes code to GitHub
2. GitHub Actions triggers build & test
3. Jenkins pulls latest code
4. Docker image is built
5. Application is deployed automatically

## 🏗️ Architecture
GitHub → GitHub Actions → Jenkins → Docker → Deployment Server

## 📊 Results
- 🚀 Reduced deployment time by ~80%
- 🔄 Fully automated build & deployment process
- ❌ Minimized manual errors

## ▶️ Setup Instructions
```bash
git clone https://github.com/your-username/ci-cd-pipeline-devops
cd ci-cd-pipeline
docker build -t devops-app .
docker run -d -p 3000:3000 devops-app
