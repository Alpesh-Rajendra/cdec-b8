# 🚀 AWS Cloud Infrastructure Tasks
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![DevOps](https://img.shields.io/badge/DevOps-blue?style=for-the-badge)
## 📌  How to Launch an AWS EC2 Instance
# Hi sir !
---
### 🛠️ Step-by-Step Deployment Guide

| Step Number | Action Details | AWS Console Location |
| :--- | :--- | :--- |
| **Step 1** | Open AWS Console & Search EC2 | Global Dashboard |
| **Step 2** | Click on **Launch Instance** | EC2 Resources Section |
| **Step 3** | Choose **Ubuntu Server 24.04 LTS** | Application & OS Images (AMI) |
| **Step 4** | Select Instance Type: **t2.micro** | Instance Type Dropdown |
| **Step 5** | Create/Select **Key Pair (.pem)** | Security Credentials |
| **Step 6** | Allow HTTP (80) & HTTPS (443) | Network Settings (Firewall) |

---
### 💻 Useful Linux Commands for EC2
After the Instance is launched, the following commands will be used to configure the terminal :
```bash
# System package list update
sudo apt update -y
# Nginx Web Server install
sudo apt install nginx -y
# Web server status check 
sudo systemctl status nginx
