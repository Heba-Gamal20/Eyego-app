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
    2. Create server.js:
### 2️⃣ Containerize the App with Docker
     1. Create a Dockerfile:
     2. Build and run the container
