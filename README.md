# Blue-Green Deployment with Jenkins, Docker, K8s & SonarQube

## 🌐 Project Overview
A production-grade Blue-Green deployment pipeline built using Jenkins, Docker, Kubernetes, and SonarQube. This approach ensures zero downtime releases and reliable rollback.

## 🧰 Tools Used
- Jenkins
- Docker
- Kubernetes (Minikube/EKS)
- SonarQube
- GitHub

## 🔁 Key Features
- Jenkins CI/CD pipeline for build/test/deploy
- Blue-Green switching using K8s services
- Code quality checks with SonarQube
- Docker image publishing and automated K8s deployment


## 🚀 Getting Started
1. Clone repo and configure Jenkinsfile
2. Set up SonarQube server and Docker Hub credentials
3. Deploy initial version (Blue), then Green and switch via K8s service


