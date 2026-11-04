# AWS-EC2-CLOUDWATCH-MONITORING-
AWS EC2 MONITERING WITH CLOUDWATCH AND SNS EMAIL ALERTS
## Project Overview
This project demonstrates monitoring an EC2 instance with CloudWatch and SNS email alerts
## Architecture
EC2 sends CPU metrics to cloudwatch 
EC2 to cloud watch to SNS to Email
## Current Status

The Cloudwatch CPU alarm currently shows "insufficient data" because the EC2 instance is stopped to minimize AWS cost
## CloudWatch and Monitoring Screenshot

![CloudWatch Alarm](Alarms%20and20%Monitoring.png)
I explored an Amazon VPC with CIDR block 172.31.0.0 slash sixteen, identified seven subnets, and reviewed the main route table. The routes send internal traffic to local and outbound traffic to an internet gateway, showing how AWS handles local versus internet-bound traffic.