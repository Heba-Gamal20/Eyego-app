# Eyego-app
Containerizing and Deploying a Node.js Application using Docker, Kubernetes, and CI/CD Pipelines on AWS and Google Cloud
## 📌 Project Overview
This project demonstrates how to develop, containerize, and deploy a **Node.js web application** using **Docker** and **Kubernetes (K8s)** on **AWS EKS** and **Google Kubernetes Engine (GKE)**. It also integrates **CI/CD automation** using **GitHub Actions**.
## 📂 Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Step-by-Step Guide](#step-by-step-guide)
  - [1️⃣ Create a Simple Node.js App](#1️⃣-create-a-simple-nodejs-app)
  - [2️⃣ Containerize the App with Docker](#2️⃣-containerize-the-app-with-docker)
  - [3️⃣ Deploy on AWS EKS](#3️⃣-deploy-on-aws-eks)
  - [4️⃣ Automate Deployment with GitHub Actions](#4️⃣-automate-deployment-with-github-actions)
  - [5️⃣ Migrate to Google Cloud (GKE) or Alibaba Cloud](#5️⃣-migrate-to-google-cloud-gke-or-alibaba-cloud)
- [Technologies Used](#technologies-used)
- [Future Enhancements](#future-enhancements)
- [Contact & Support](#contact--support)

## 📂 Project Structure
- 📜 **server.js** – The Node.js web application  
- 🐳 **Dockerfile** – Docker build instructions  
- 📄 **deployment.yaml** – Kubernetes Deployment and Service definition
- ⚙️ **.github/workflows/deploy.yml** – GitHub Actions CI/CD workflow
  
- 📘 **README.md** – Documentation
## 🚀 Step-by-Step Guide

### 1️⃣ Create a Simple Node.js App 
     1. Initialize a **Node.js project**
      npm init -y  
      npm install express 
    2. Create server.js.
### 2️⃣ Containerize the App with Docker
     1. Create a Dockerfile.
     2. Build and run the container.
###   3️⃣ Deploy on AWS EKS
       1. Create an ECR repository
       2. Authenticate Docker with AWS ECR
       3. Push the Docker Image to AWS ECR
       4. Create an AWS EKS Cluster.
       5. Deploy the App to Kubernetes.
          *Create a deployment.yaml file
          *Apply the deployment to Kubernetes
        6.   Expose the App via LoadBalancer
           *Create a service.yaml file
           *Apply the service to Kubernetes
           *Get the external LoadBalancer IP
           *Access the app using the external IP
###  4️⃣ Automate Deployment with GitHub Actions
      Create .github/workflows/deploy.yml

###   5️⃣ Migrate to Google Cloud (GKE)
    1.   Create a GKE cluster
    2.  Build and push Docker image to Google Container Registry
    3.  Deploy using Kubernetes
    4.  

