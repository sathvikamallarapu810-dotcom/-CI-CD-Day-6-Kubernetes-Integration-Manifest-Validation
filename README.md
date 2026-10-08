🚀 CI/CD Day 6 — Kubernetes Integration & Manifest Validation

Today I completed the final stage of my CI/CD foundation project.

### What I worked on
- Created a Kubernetes Deployment and Service manifest
- Deployed the application to Minikube
- Verified Kubernetes rollout and Pod health
- Tested the application through a NodePort Service
- Integrated the Kubernetes manifest into the GitHub repository
- Added Kubernetes manifest validation to GitHub Actions
- Fixed YAML indentation and workflow issues
- Verified the complete GitHub Actions pipeline successfully

### CI/CD Pipeline

Git Push
   ↓
GitHub Actions
   ↓
Build
   ↓
Test
   ↓
Docker Build
   ↓
Docker Hub Push
   ↓
Kubernetes Manifest Validation
   ↓
Success ✅

### Kubernetes Flow

Docker Hub
   ↓
Kubernetes Deployment
   ↓
Pod
   ↓
NodePort Service
   ↓
Browser
   ↓
Hello from CI/CD ✅

Docker Image:
sathvika1203/cicd-day4-app:latest

Kubernetes:
- Deployment: day5-app
- Service: day5-service
- Cluster: Minikube

GitHub Repository:
sathvikamallarapu810-dotcom/cicd-day1

CI/CD foundation completed successfully! 🚀

Next: Terraform → Python/Shell/Boto3 → Cloud Security
