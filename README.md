# DevOps Project – CI/CD Pipeline with Docker, Kubernetes & AWS EKS

## 🔧 Technologies Used
- GitHub Actions (CI/CD automation)
- Docker & Docker Compose (Containerization)
- Kubernetes (Orchestration)
- AWS EKS (Cloud Deployment)
- Flask (Backend) & React (Frontend)
- MySQL (Database)

## 🚀 Features
- Full-stack application: Flask API + React UI + MySQL DB
- Dockerized Microservices with Docker Compose
- CI/CD Pipeline using GitHub Actions
- Kubernetes Manifests for deployment
- Production-ready deployment on AWS EKS

## 🧠 Project Journey (My Learning Path)
1. 🐳 **Docker:** Containerized the backend, frontend, and MySQL using Docker Compose  
2. ☸️ **Kubernetes:** Migrated the entire app to local Kubernetes cluster with YAML manifests  
3. ☁️ **AWS EKS:** Deployed on Amazon Elastic Kubernetes Service using `kubectl` and `eksctl`

## 📦 Project Structure
```
/backend          # Flask App  
/frontend         # React UI  
/docker-compose.yml  
/Dockerfile.*     # Backend & Frontend Dockerfiles  
/.github/workflows # CI/CD pipeline using GitHub Actions  
/k8s/             # Kubernetes YAML files  
```

## ⚙️ How to Run Locally (Docker Compose)
```bash
git clone https://github.com/Misbah-Ashiq/project.git
cd project
docker-compose up --build
```

## ☸️ How to Deploy on Kubernetes (Minikube or EKS)
```bash
kubectl apply -f k8s/
```
> 💡 Note: AWS credentials and EKS cluster must be configured beforehand. Use `eksctl`, `kubectl` & `AWS CLI`.
