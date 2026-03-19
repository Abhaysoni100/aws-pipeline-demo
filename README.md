# 🚀 AWS CI/CD Pipeline for Static Website Deployment

This project demonstrates a complete **CI/CD pipeline** using AWS services to automatically deploy a static website.

---

## 📌 Project Overview

A simple HTML website is deployed on Amazon S3 using an automated pipeline:

GitHub → AWS CodePipeline → AWS CodeBuild → Amazon S3

Every time code is pushed to GitHub, the pipeline triggers automatically and deploys the updated website.

---

## 🛠️ Technologies Used

- AWS CodePipeline
- AWS CodeBuild
- Amazon S3 (Static Website Hosting)
- GitHub
- WSL (Windows Subsystem for Linux)

---

## ⚙️ Architecture

1. Code is pushed to GitHub repository  
2. CodePipeline detects changes  
3. CodeBuild builds the project using `buildspec.yml`  
4. Files are deployed automatically to S3 bucket  
5. Website is updated instantly  

---

## 📂 Project Structure

aws-pipeline-demo/
│── index.html
│── buildspec.yml
│── README.md


---

## 📄 buildspec.yml

```yaml
version: 0.2

phases:
  build:
    commands:
      - echo "Building..."

artifacts:
  files:
    - '**/*'

**Live Website **
http://abhay-pipeline-demo-123.s3-website.ap-south-1.amazonaws.com
    


 **Key Features**

Fully automated CI/CD pipeline

Continuous deployment on every Git push

Serverless hosting using Amazon S3

Real-time updates without manual upload


**What I Learned**

Setting up AWS CodePipeline and CodeBuild

Integrating GitHub with AWS

Automating deployments using CI/CD

Hosting static websites on S3


 **Author**

Abhay Soni
abhaysoni9527@gmail.com

LinkedIn: https://www.linkedin.com/in/abhay-soni-5b357b24b

GitHub: https://github.com/Abhaysoni100
