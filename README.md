# 🌐 AWS CloudFront Portfolio Project  
### Static Website Hosting using **Amazon S3 + CloudFront (CDN)**

This project demonstrates how I deployed my personal portfolio website using **AWS S3**, **CloudFront**, and **IAM**.  
It showcases **secure, scalable, globally distributed static hosting** — essential skills for AWS Cloud Engineer & Solutions Architect roles.

---

## 🚀 Project Overview

- Website hosted on **Amazon S3 (Static Website Hosting)**
- Distributed globally using **Amazon CloudFront CDN**
- HTTPS enforced for secure access
- S3 bucket configured with correct **bucket policies**
- Clean folder structure with 2023 personal portfolio website

---

## 🏗️ Architecture Diagram

```mermaid
flowchart TD
    User((User)) -->|Requests Website| CF[CloudFront CDN]
    CF -->|Fetches Content| S3[S3 Bucket (Static Website)]
    S3 -->|Serves HTML/CSS/Images| CF
