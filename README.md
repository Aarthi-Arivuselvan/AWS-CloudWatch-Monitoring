A complete monitoring and alert automation project using Amazon CloudWatch and SNS.
This project demonstrates installing the CloudWatch agent on an EC2 instance, collecting system metrics, creating alarms, and setting up email notifications.

## Overview

This project explains how to monitor an Amazon EC2 instance using CloudWatch Metrics, CloudWatch Agent, SNS, and CloudWatch Alarms.
It covers installing the CloudWatch agent, collecting CPU, memory, and disk metrics, and configuring automated alerts through Amazon SNS.

## Project Highlights

Installed and configured the CloudWatch Agent on an EC2 instance
Collected system metrics including CPU utilization, memory usage, and disk usage
Visualized instance performance through CloudWatch graphs and dashboards
Created an SNS Topic and enabled email subscription for alert notifications
Configured a CloudWatch Alarm to trigger notifications when CPU usage crossed a threshold
Demonstrated real-time monitoring and alerting for cloud infrastructure

## Project Screenshots

| Description | Screenshot |
|------------|------------|
| VPC Created for EC2 Monitoring | ![VPC Created](Step1_VPC_Creation_Preview.PNG) |
| IAM Role for CloudWatch Agent | ![IAM Role](Step2_IAM_Role_EC2CloudWatchRole.png) |
| EC2 Instance Details | ![Instance Details](Step3_EC2_Instance_Details.png) |
| Apache Web Server Installed | ![Apache Installed](Step4_Apache_Installed.png) |
| SSH Connection to EC2 | ![SSH Connected](Step4_SSH_Connected.png) |
| Web Page Working on EC2 | ![Web Page Working](Step4_WebPage_Working.png) |
| CloudWatch Metrics Visible | ![Metrics Visible](Step5_CloudWatch_Metrics_Visible.png) |
| CloudWatch Agent Installed | ![Agent Installed](Step5_CloudWatchAgent_Installed.png) |
| CloudWatch Agent Started | ![Agent Started](Step5_CloudWatchAgent_Started.png) |
| CloudWatch Agent Status Check | ![Agent Status](Step5_CloudWatchAgent_Status.png) |
| CloudWatch Alarm Created | ![Alarm Created](Step6_Alarm_Created.png) |
| SNS Subscription Confirmed | ![SNS Subscription](Step6_SNS_Subscription_Confirmed.png) |
| SNS Topic Created | ![SNS Topic](Step6_SNS_Topic_Created.png) |

## Tools & AWS Services Used

Amazon EC2 – Linux instance for hosting the CloudWatch Agent
Amazon CloudWatch – Metrics, dashboards, and alarms
CloudWatch Agent – Collected memory, disk, and detailed system metrics
Amazon SNS (Simple Notification Service) – Email alert notifications
IAM (Identity & Access Management) – Role for CloudWatch and SNS access
VPC, Subnets, Security Groups – Networking & access control

## Skills Gained

Infrastructure monitoring
CloudWatch metrics collection and visualization
Creating alarms for incident detection
SNS-based alert automation
IAM role creation and permissions management
Linux system administration basics
Debugging CloudWatch Agent and EC2 configurations
Real-world cloud incident response workflow

## 💚 Author
Aarthi Arivuselvan
AWS Cloud Enthusiast ☁️ | Linux Learner 🐧
📧 Contact: aarthi11920@gmail.com
