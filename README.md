# 🌐 Personal Portfolio Hosting on AWS (S3 + CloudFront + IAM Policies)

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

## 🏗️ Architecture Diagram

![AWS Architecture](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/architecture.png)


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
  ![s3 with web files](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/s3%20with%20web%20files.png)
  ![s3 static web hosting](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/s3%20static%20web%20hosting.png)



![edited bucket policy](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/edited%20bucket%20policy.png)

![make images public using acl](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/make%20images%20public%20using%20acl.png)
![edited public access](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/edited%20public%20acess.png)

![edited static web hosting](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/edited%20static%20web%20hosting.png)
---
-  Hosting Live Website
  ![web hosting live amz 1](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20amz%201.png)

![web hosting live amz 2](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20amz%202.png)

![web hosting live amz 3](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20amz%203.png)

![web hosting live amz 4](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20amz%204.png)

---
- CloudFront Distribution Screenshot
  ![Created new cloud front distribution](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/Created%20new%20cloud%20front%20distrubution.png)
- web hosting live with cloudfront
![web hosting live with cloudfront 1](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20with%20cloudfront%201.png)

![web hosting live with cloudfront 2](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/web%20hosting%20live%20with%20cloudfront%202.png)
---
- IAM User Screenshot
  ![iam user created](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/iam%20user%20created.png)

![Creating iam access key](https://raw.githubusercontent.com/AbhishekBhosale02/aws-cloudfront-portfolio-project/main/screenshots/Creating%20iam%20acess%20key.png)

---
- AWS CLI on CMD
  
  

---
## 🧑‍💻 Author
**Abhishek Bhosale**  
Cloud & DevOps Learner  






