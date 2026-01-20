# DevOps Portfolio – Terraform & CI/CD

This project demonstrates hands-on DevOps skills using Terraform, AWS, and GitHub Actions.
It shows how to provision infrastructure using Infrastructure as Code (IaC) and automate
testing and validation using a CI/CD pipeline.

---

## Technologies Used
- Terraform
- AWS EC2
- GitHub Actions
- Linux
- Git

---

## Terraform Infrastructure

This project uses Terraform to create and manage AWS infrastructure using separate
environment folders (dev and prod).

### Project Structure
Below is the Terraform project structure used in this portfolio:

![Terraform Project Structure](terraform/terraform-project-structure.png)

---

## AWS Resources

An EC2 instance was created using Terraform.  
The screenshot below shows the instance details from the AWS Console.

![AWS EC2 Instance](aws/aws-ec2-instance.png)

---

## CI/CD Pipeline (GitHub Actions)

A CI pipeline was implemented using GitHub Actions to automatically validate Terraform
code on every push.

### CI/CD Evidence
The following screenshots show the CI/CD pipeline in action:

![CI README Preview](ci/ci-readme-preview.png)
![CI Workflow Logs](ci/ci-workflow-logs.png)
![CI Pipeline Success](ci/ci-github-actions-success.png)

---

## What This Project Demonstrates
- Infrastructure provisioning using Terraform
- Environment separation (dev and prod)
- AWS EC2 management
- CI/CD automation with GitHub Actions
- Clean project organization and documentation
>>>>>>> ae4bb28 (Initial DevOps portfolio with Terraform and CI/CD)
