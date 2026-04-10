🚀 AWS CloudFormation DevOps Project – Noor Mohammad

📌 Project Overview

This repository contains multiple AWS projects implemented using Infrastructure as Code (CloudFormation).

It includes:

- 🌐 Static Website Hosting using S3
- 🖥️ EC2 Instance Deployment with Nginx

---

🌐 Project 1: AWS S3 Static Website Hosting

📖 Description

This project demonstrates how to deploy a static website on AWS S3 using CloudFormation.

⚙️ Features

- Create S3 bucket automatically
- Enable static website hosting
- Upload HTML & CSS files
- Configure bucket policy for public access
- Access website via S3 endpoint

🛠️ Technologies Used

- AWS S3
- AWS CloudFormation
- HTML5, CSS3
- Git & GitHub

---

🖥️ Project 2: EC2 Deployment using CloudFormation

📖 Description

This project demonstrates launching an EC2 instance with a custom Security Group and deploying a web server.

⚙️ Features

- EC2 instance creation using CloudFormation
- Automatic Security Group creation
- SSH (Port 22) access enabled
- HTTP (Port 80) access enabled
- Nginx web server installation

---

🚀 EC2 Access Details

- Public IP: "18.61.15.186"
- Username: "ubuntu"
- Key Pair: "noor-key.pem"

🔐 SSH Command

ssh -i noor-key.pem ubuntu@18.61.15.186

---

🌐 Web Access

After installing nginx:

http://18.61.15.186

---

📂 Project Structure

CloudFormation/
 ├── ec2.yaml
 ├── s3.yaml
 ├── index.html
 ├── style.css
 └── README.md

---

⚙️ Deployment Steps

🖥️ EC2 Deployment

1. Go to AWS Console → CloudFormation
2. Create stack using "ec2.yaml"
3. Provide key pair: "noor-key"
4. Launch stack

---

🌐 S3 Deployment

1. Create stack using "s3.yaml"
2. Upload website files
3. Enable static hosting

---

💻 Local Setup (WSL Ubuntu)

cd ~/CloudFormation
git init
git add .
git commit -m "Initial commit - AWS DevOps Project"

---

🌐 Push to GitHub

git remote add origin https://github.com/<your-username>/aws-cloudformation-devops-project.git
git branch -M main
git push -u origin main

---

⚠️ Important

- Do NOT upload ".pem" file
- Add ".gitignore":

echo "*.pem" >> .gitignore

---

📸 Output

- EC2 instance running
- Nginx web server accessible
- S3 static website deployed

---

👨‍💻 Author

Noor Mohammad
DevOps Learner 🚀