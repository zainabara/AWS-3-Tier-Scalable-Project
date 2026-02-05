# **AWS 3-Tier Scalable Project**

## 📌 Project Overview

This project demonstrates the implementation of a scalable and secure **3-Tier Architecture on AWS**, designed to support production-level workloads with high availability, fault tolerance, and robust network security.

![Architecture-diagram](https://github.com/user-attachments/assets/224a0dfc-e102-4987-85f1-35121b0b3be0)


## 🏗 Architecture Overview

### **AWS Services Used**

* Amazon VPC
* Public & Private Subnets
* Internet Gateway & NAT Gateway
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* EC2 Instances
* CloudFront (CDN)
* Security Groups
* IAM Roles & Policies

### **Architecture Flow**

1. Users access the application through **CloudFront** for improved global performance.
2. CloudFront forwards requests to the **Application Load Balancer (ALB)**.
3. The ALB distributes traffic to EC2 instances deployed inside **private subnets**.
4. A **NAT Gateway** enables secure outbound traffic for private instances.
5. The **Auto Scaling Group** ensures the application scales automatically based on load.

---

## 📊 Key Features

* Multi-AZ **High Availability**
* **Automatic Scaling** of EC2 instances
* Secure architecture using **private subnets**
* Faster global delivery with **CloudFront**
* Optimized design suitable for production environments

---

## 🧪 Health Monitoring

* ALB performs continuous **health checks** on backend EC2 instances
* Unhealthy instances are automatically replaced by the **Auto Scaling Group**

---

## 🧹 Cleanup

All AWS resources used during the project were **terminated after validation** to prevent unnecessary billing.
Architecture diagrams and configuration steps accurately represent the implemented setup.

---

## 🚀 Real-World Applications

This architecture is commonly used for:

* Web applications
* E-commerce platforms
* Company websites
* APIs and microservices

---

## 🧠 Skills Demonstrated

* VPC & Subnet Architecture
* Load Balancing & Auto Scaling
* CloudFront CDN Integration
* Infrastructure Security Best Practices
* Cost Optimization & Post-Project Cleanup

---

## 👤 Author

**Zainab Ara**

