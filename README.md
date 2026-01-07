# AWS ECS Fargate – LMS Frontend Deployment

This project demonstrates deploying a containerized LMS frontend application to AWS ECS Fargate behind an Application Load Balancer.

## 🚀 Tech Stack
- Docker (Nginx)
- AWS ECS (Fargate)
- Amazon ECR
- Application Load Balancer
- AWS VPC & Security Groups

## 📌 What I Did
- Created a Docker image using Nginx to serve a static LMS frontend
- Built the image for linux/amd64 using Docker Buildx
- Pushed the image to Amazon ECR
- Created an ECS Fargate task definition and service
- Configured ALB, target groups, and security groups
- Successfully deployed and accessed the application publicly
- Cleaned up resources to avoid unnecessary costs

## 🖼 Screenshots
Screenshots of deployment, ECS service status, ALB access, and Docker build logs are included in the `/screenshots` folder.

## 💡 Key Learnings
- Containerization using Docker
- ECS Fargate service lifecycle
- ALB routing and health checks
- Cloud cost awareness and cleanup
- End-to-end production deployment workflow

## 📍 Status
Project completed and documented for learning and portfolio purposes.
