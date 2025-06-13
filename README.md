# Task 2 - Cloud Monitoring and Alerts

## 🔧 Tools Used
- AWS CloudWatch
- AWS S3

## 📌 Objective
Set up monitoring for a cloud-based application using AWS CloudWatch and configure alerts for specific metrics.

## ✅ What I Did
- Created a CloudWatch dashboard to monitor `S3` bucket metrics like `NumberOfObjects`
- Configured a CloudWatch alarm to trigger when requests exceed a threshold
- Setup SNS email notifications for the alarm

## 🔔 Alert Configured For:
- **Metric:** S3 → NumberOfObjects
- **Threshold:** > 5 requests
- **Action:** Email alert via SNS

## 📊 Dashboard Preview
![Dashboard](./dashboard.png)

## 🚨 Alarm Configuration
![Alarm](./alarm.png)

## 📩 Email Notification
![Email](./alert-email.png)

