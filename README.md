# 🌐 Cloud Networking Project

A hands-on project demonstrating the design, deployment, and testing of a secure **Virtual Private Cloud (VPC)** architecture in Amazon Web Services (AWS).

This repository documents how to configure isolated network environments, apply security controls, and validate connectivity using common networking tools.

---

## 📌 Project Overview

This project focuses on:
- Designing a custom VPC with public and private subnets
- Configuring route tables and an Internet Gateway for controlled traffic flow
- Deploying EC2 instances in different subnets to simulate real-world scenarios
- Testing connectivity both within the VPC and to external internet resources
- Applying and troubleshooting security rules using Security Groups and Network ACLs

---

## ⚙️ Key Components

- **Amazon VPC**: Private, isolated network in the cloud  
- **EC2 Instances**: Virtual machines for connectivity testing  
- **Security Groups & NACLs**: Fine-grained traffic control  
- **Route Tables & IGW**: Manage internal and external routing  
- **Tools**:  
  - `ping` – test basic network reachability  
  - `curl` – verify HTTP/HTTPS access and API connectivity

---

## 🧪 What We Tested

✅ EC2-to-EC2 connectivity within the same subnet  
✅ Connectivity across different subnets  
✅ Internet access from instances in public subnets  
✅ Impact of adding/removing security group and NACL rules

---

## 🚀 How to Use

> 📌 **Note:** This project assumes you have basic familiarity with AWS and access to an AWS account.


