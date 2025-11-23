**End-to-End DevOps Project — Flask + MySQL | Docker | Docker Compose | Jenkins CI/CD**

Hands-On Portfolio Project for DevOps Engineers

Modern applications demand faster delivery, scalability & reliability. DevOps solves this by combining development + operations with automation. In this project, I implemented a complete CI/CD pipeline for a two-tier application (Flask + MySQL) using Jenkins, Docker, and Docker Compose.

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/032987cb-d60f-4990-a4bf-e5fdc104ab77" />


🧱 🔹 Project Overview

The goal of this project is to automate the deployment of a Python Flask web application connected to a MySQL database.

Whenever new code is pushed to GitHub:

Jenkins automatically pulls the latest code

Jenkins builds a Docker image for the Flask application

Jenkins deploys the system using Docker Compose

Both containers — Flask API and MySQL DB — start together inside a Docker network

This ensures No manual deployments. No environment mismatch. Immediate updates.




⚙️ 🔹 Tech Stack

| Category                   | Tools              |
| -------------------------- | ------------------ |
| Backend Framework          | Python Flask       |
| Database                   | MySQL              |
| Source Code                | GitHub             |
| CI/CD Automation           | Jenkins            |
| Containerization           | Docker             |
| Multi-Container Deployment | Docker Compose     |
| Health Monitoring          | Docker Healthcheck |
| OS                         | Linux – Ubuntu     |



🏗 🔹 Architecture

A Two-Tier Architecture is used:

Tier 1 → Flask Application

Tier 2 → MySQL Database



🔁 🔹 CI/CD Pipeline Breakdown
Stage	Action
Build	Jenkins pulls code and builds Docker image
Deploy	Docker Compose starts both containers
Verification	Healthcheck monitors Flask & MySQL
Feedback	Jenkins logs confirm build & deployment status
