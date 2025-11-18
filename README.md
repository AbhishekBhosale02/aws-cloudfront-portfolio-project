# 🌐 Personal Portfolio Hosting on AWS (S3 + CloudFront)

This project demonstrates how to deploy a **static portfolio website** using **Amazon S3**, deliver it globally using **Amazon CloudFront**, and secure deployments using **IAM** & **AWS CLI**.


## 🚀 Live Website
🔗 **https://duwy3jm9cuhi.cloudfront.net**


## 🧰 AWS Services Used

### **1. Amazon S3**
- Stores the static website files (HTML, CSS, JS, Images)
- Static website hosting enabled

### **2. Amazon CloudFront**
- Global CDN to speed up website delivery
- HTTPS enabled
- Origin: S3 Bucket
- Improved caching & global availability

### **3. AWS IAM**
- IAM User created for secure deployments
- Access Key & Secret Key generated for CLI usage

### **4. AWS CLI**
- Used for uploading and syncing website files
- Used for CloudFront cache invalidation

---

## 🏗️ Architecture Diagram: 

![AWS Architecture](https://raw.githubusercontent.com/your-username/your-repo/main/A_2D_digital_diagram_illustrates_the_architecture_.png)


(Replace with your PNG file — name it `architecture.png`)

---

## 📂 Folder Structure: 

/website
  ├── index.html
  ├── about.html
  ├── contact.html
  ├── assets/
  ├── images/
  └── css/


## 📝 Steps Followed: 

### **1. Create S3 Bucket**
 Unique bucket name
 Public access disabled
 Static website hosting enabled
 Files uploaded

### **2. Create CloudFront Distribution**
 Origin: S3 bucket
 SSL (HTTPS) enabled
 Default root: index.html
 Wait for distribution to deploy
 Test CloudFront link

### **3. Create IAM User**
 Programmatic access enabled
 Permissions: Custom group + policies
 Access key downloaded (CSV)
 Configured using `aws configure`

### **4. Learn how to Upload Website Using AWS CLI**


## 📸 Screenshots 
- S3 Static Hosting Screenshot
- CloudFront Distribution Screenshot
- IAM User Screenshot
- Website live screenshot

---

## 🧑‍💻 Author
**Abhishek Bhosale**  
Cloud & DevOps Learner  
