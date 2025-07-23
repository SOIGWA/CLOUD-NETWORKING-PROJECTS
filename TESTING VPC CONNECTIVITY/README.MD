
# Testing VPC Connectivity

**Author:** Andy Ombasa  
**Project Time:** ~1 hour  
**Platform:** [NextWork](https://nextwork.org)

---

## 📌 Project Overview

This project demonstrates how to test connectivity within an AWS Virtual Private Cloud (VPC).  
It covers connecting to EC2 instances, testing communication between servers, troubleshooting connectivity issues, and checking internet access using common tools like `ping` and `curl`.

---

## 🌐 What is Amazon VPC?

Amazon Virtual Private Cloud (VPC) allows you to create an isolated, private network in AWS.  
It helps you securely manage cloud resources by controlling:

- IP address ranges
- Subnets
- Route tables
- Security groups

---

## ✅ What I Did

- Connected to a **NextWork** public EC2 server
- Verified **EC2-to-EC2 connectivity** within the same subnet
- Tested **internet connectivity** from the instance

---

## ⚙️ Key Steps & Tools

### Connecting to EC2
- Used **EC2 Instance Connect** for browser-based SSH.
- Resolved initial SSH errors by adding an **inbound security group rule** on port `22` from my IP.

### Testing Connectivity Between Servers
- Used the `ping` command to test if servers could reach each other over the network.
- Allowed **ICMP traffic** in the security group to enable ping.

### Verifying Internet Access
- Used `curl` to test connectivity to external websites and APIs.
- Example command:
  ```bash
  curl https://learn.nextwork.org/projects/aws-host-a-website-on-s3
