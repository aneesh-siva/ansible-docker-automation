# 🚀 Ansible + Docker Automation Project

This project demonstrates an end-to-end DevOps automation workflow using **Ansible** and **Docker**. It automates the complete process of setting up infrastructure and deploying a containerized application using Infrastructure as Code (IaC).

---

## 📌 Project Overview

The goal of this project is to eliminate manual configuration and achieve a fully automated deployment pipeline.

🔹 Automates Docker installation  
🔹 Deploys a containerized application  
🔹 Uses Ansible roles for modular design  
🔹 Ensures repeatable and consistent deployments  

---

## 🛠️ Tech Stack

- **Ansible** – Automation & Configuration Management  
- **Docker** – Containerization  
- **WSL (Ubuntu)** – Execution Environment  
- **Node.js** – Application Runtime

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/aneesh-siva/ansible-docker-automation.git
cd ansible-docker-automation

---
2️⃣ Install Dependencies

sudo apt update
sudo apt install ansible docker.io -y

3️⃣ Run the Playbook
ansible-playbook -i inventory.ini site.yml --ask-become-pass


4️⃣ Access the Application

Open your browser and navigate to:

http://localhost:3000


🔁 Workflow

1. Ansible playbook is executed
2. Docker is installed and started
3. Node.js Docker image is pulled
4. Container is created and started
5. Application is deployed inside container
6. Port is exposed (3000)
7. Application becomes accessible in browser


🎯 Features

✅ Fully automated deployment
✅ Modular Ansible roles (industry standard)
✅ Idempotent execution
✅ Containerized application
✅ No manual intervention required



🧠 Key Learnings

1. Infrastructure as Code (IaC)
2. Ansible Playbooks & Roles
3. Docker container lifecycle management
4. Linux environment setup (WSL)
5. Debugging real-world DevOps issues


🚀 Future Enhancements

CI/CD pipeline integration using Jenkins
Kubernetes deployment (Minikube)
Monitoring using Prometheus & Grafana


👨‍💻 Author
Aneesh Siva


⭐ Acknowledgment
This project was built using the free trial provided by Red Hat Ansible Automation Platform.
