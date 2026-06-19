# DOCKER-PROJECT-WITH-JAVA-APPLICATION
End-to-End DevSecOps CI/CD Pipeline Project

This project demonstrates a complete DevSecOps CI/CD pipeline using Jenkins, GitHub, Maven, SonarQube, Docker, Trivy, Docker Hub, and Docker Swarm.
Architecture / Pipeline Flow
 
Project Overview
Automated software delivery lifecycle with integrated code quality validation, security scanning, containerization, and deployment.

Tools & Technologies
GitHub, Jenkins, Maven, SonarQube, Docker, Trivy, Docker Hub, Docker Swarm, Linux.
CI/CD Workflow
1. Source Code Checkout
2. SonarQube Analysis
3. Maven Build
4. Docker Image Creation
5. Trivy Vulnerability Scan
6. Docker Hub Push
7. Docker Swarm Deployment

 Flowchart:  

┌─────────────┐
│   GitHub    │
│ Source Code │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│   Jenkins   │
│ Pipeline    │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ SonarQube   │
│ Code Review │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Maven Build │
│ & Package   │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Docker      │
│ Build Image │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Trivy Scan  │
│ Security    │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Docker Hub  │
│ Push Images │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│Docker Swarm │
│ Deployment  │
└─────────────┘

Key Achievements
Implemented DevSecOps practices, automated deployments, vulnerability scanning, and production-style container orchestration.


