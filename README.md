# 🚀 **DevOps Real-time Project: Swiggy Application Deployment**

Welcome to the **Swiggy Application Deployment project**! In this project, I have leveraged modern **DevSecOps tools** to **automate, secure, and optimize** the deployment pipeline for a feature-rich Swiggy-like application. 🎉  

This project showcases **Infrastructure as Code (IaC), Continuous Integration (CI), Continuous Deployment (CD), Containerization, and Security Best Practices** in a real-world scenario.

## 🔥 **Tech Stack & Tools Used**
The project integrates multiple DevOps tools for **infrastructure provisioning, CI/CD automation, security analysis, and container management**:

1. **Terraform** – Infrastructure as Code (IaC) for cloud provisioning  
2. **GitHub** – Version control and source code repository  
3. **Jenkins** – Continuous Integration & Deployment (CI/CD)  
4. **SonarQube** – Static code analysis for code quality  
5. **OWASP ZAP** – Security vulnerability scanning  
6. **Trivy** – Container image vulnerability scanning  
7. **Docker & DockerHub** – Containerization and image hosting  

---

## 📂 **Project Architecture**
The **Swiggy Application Deployment** project follows a structured **CI/CD pipeline**:

### **✅ Steps in the Workflow**
1. **Code Management**: Developers push the latest application code to GitHub.  
2. **Automated Build & Testing**: Jenkins automatically triggers builds and runs unit tests.  
3. **Static Code Analysis**: SonarQube scans for code quality issues.  
4. **Security & Vulnerability Checks**:
   - **OWASP ZAP** performs penetration testing.
   - **Trivy** scans Docker images for vulnerabilities.  
5. **Containerization**: Docker is used to build and package the application.  
6. **Deployment to Cloud**: The containerized app is deployed using **Terraform & AWS ECS/Kubernetes**.  

---

## 🛠️ **Setup & Installation**
### **1️⃣ Prerequisites**
Ensure you have the following installed:
- [Terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
- [Jenkins](https://www.jenkins.io/download/)
- [Docker](https://docs.docker.com/get-docker/)
- [SonarQube](https://www.sonarqube.org/)
- [Trivy](https://aquasecurity.github.io/trivy/)
- [OWASP ZAP](https://www.zaproxy.org/download/)
- An **AWS Account** with necessary IAM permissions

### **2️⃣ Infrastructure Provisioning with Terraform**
Use Terraform to set up AWS resources:
```bash
terraform init
terraform plan
terraform apply

## Architecture
![image](https://github.com/user-attachments/assets/46f4a984-e1d9-4cfb-9ec7-3430a71cd605)

---
