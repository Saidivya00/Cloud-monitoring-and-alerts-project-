# 📊 Cloud Monitoring and Alerts Project – AWS CloudWatch

This project demonstrates how to set up real-time monitoring and alerting for a cloud-based application hosted on **Amazon Web Services (AWS)** using **CloudWatch** and **Simple Notification Service (SNS)**.

---

## 🎯 Objectives

- Deploy and monitor a web application on EC2
- Install and configure CloudWatch Agent
- Create a CloudWatch dashboard with key metrics
- Configure alarms for high CPU and disk usage
- Send automated email notifications using SNS

---

## 🛠️ Tools Used

- Amazon Web Services (AWS)
- AWS CloudWatch
- EC2 Linux Instance (Apache or Node.js app)
- CloudWatch Agent
- SNS (Simple Notification Service)

---

## 🧰 Steps Followed

### 1. Launch EC2 Instance  
- Deployed a sample web application on an EC2 instance  
- Enabled public access for testing and monitoring  

### 2. Install and Configure CloudWatch Agent  
- Connected to EC2 via SSH  
- Installed the CloudWatch Agent  
- Configured to monitor CPU, Disk, and Network metrics  

---
## 3.Set Up CloudWatch Dashboard

Created dashboard named: CloudApp-Monitor

Added widgets for:

CPU Utilization

Disk Usage

Network Traffic

Application health (if needed)



 ## 4. Create CloudWatch Alarms

Alarm 1: CPU Utilization > 80% for 5 minutes

Alarm 2: Disk Usage > 70%

Triggered actions via SNS


## 5. Configure SNS for Notifications

Created SNS topic: CloudAppAlerts

Subscribed email: sai.divya@example.com

Confirmed subscription via email

Linked SNS topic to CloudWatch alarms



---

## ✅ Testing and Results

Simulated CPU load using the stress tool

Monitored real-time metrics on dashboard

Alarm triggered when thresholds were breached

Email alert received successfully



---

## 📦 Deliverables

Component	Description

Dashboard	CloudApp-Monitor
Metrics Monitored	CPU, Disk, Network
Alerts	CPU > 80%, Disk > 70%
Notifications	Email via SNS



---

## 📄 Report Download

👉 Download Project 2 Report (PDF)


---

## 📌 Conclusion

This project demonstrates the successful setup of AWS CloudWatch for monitoring a cloud-hosted application. Real-time metrics, visual dashboards, and automated alerts ensure system reliability and proactive infrastructure management. This is an essential DevOps practice for modern cloud-based systems.
