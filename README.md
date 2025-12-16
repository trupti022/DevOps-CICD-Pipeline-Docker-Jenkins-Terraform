# CI/CD Pipeline using Docker, Jenkins, Kubernetes & Terraform

## Overview
End-to-end DevOps pipeline to build, test, and deploy a production application using Docker, Jenkins, Kubernetes, Terraform, and Ansible.

## Workflow
1. Application code pushed to GitHub
   
2. Jenkins Freestyle Job builds Docker image
 
3. App tested on port 85
 
4. On success, image pushed to DockerHub
 
5. Jenkins pipeline deploys app to Kubernetes (NodePort)
 
6. Infrastructure provisioned using Terraform
 
7. Java installed using Ansible

## Technologies
Docker | Jenkins | Kubernetes | Terraform | Ansible | AWS EC2
