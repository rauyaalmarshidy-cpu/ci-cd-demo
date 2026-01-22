# Cloud & DevOps Portfolio

This portfolio demonstrates hands-on experience with **Terraform**, **AWS**, and **CI/CD using GitHub Actions**.  

It showcases my skills in building cloud infrastructure, automating workflows, and documenting projects professionally.

---

## 🚀 Technologies Used
- Terraform
- AWS (EC2)
- GitHub Actions (CI/CD)
- Linux
- Git & GitHub

---

## 🏗️ Terraform Project

This project demonstrates provisioning cloud resources using Terraform with a clear and modular structure.

### Terraform Structure
![Terraform Structure](screenshots/terraform-structure.png)

### AWS EC2 Instance
![AWS EC2 Instance](screenshots/aws-ec2-instance.png)

---

## 🔄 CI/CD Pipeline (GitHub Actions)

Automation using GitHub Actions to streamline deployment and validation.

### CI Success
![CI Success](screenshots/ci-github-actions-success.png)

### Workflow Logs
![Workflow Logs](screenshots/ci-workflow-logs.png)

### README Preview
![README Preview](screenshots/ci-readme-preview.png)

---

## ✅ Summary

This portfolio demonstrates:

- Infrastructure as Code using Terraform  
- Provisioning cloud resources on AWS  
- CI/CD automation with GitHub Actions  
- Clear structure and professional documentation

## Kubernetes Project

This project demonstrates a simple Kubernetes deployment using Minikube.

### Nginx Deployment
- Deployed 2 replicas of Nginx using a Deployment.
- Exposed the application using a NodePort Service.

### Screenshots

**1. Nginx running in browser:**  
![Nginx Page](screenshots/k8-nginx-page.png)

**2. Cluster status (pods + service):**  
![Cluster Status](screenshots/k8-cluster-status.png)

### Commands used
```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get pods
kubectl get svc
minikube service nginx-service --url
