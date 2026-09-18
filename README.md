# Highly Available AWS Web Application

A hands-on AWS infrastructure project demonstrating a highly available application tier using private EC2 instances, an Application Load Balancer, Auto Scaling, Amazon RDS, CloudWatch monitoring, Route 53 DNS, and ACM-based HTTPS.

## Project Overview

This project was built to practice designing, deploying, monitoring, and troubleshooting a production-style AWS web application architecture.

The application tier runs across two Availability Zones and is managed by an Auto Scaling Group. An internet-facing Application Load Balancer distributes traffic to private EC2 instances, while Amazon RDS provides a private MySQL database tier.

CloudWatch and SNS were used for health monitoring and alerting. Route 53 and AWS Certificate Manager were used to provide custom-domain access over HTTPS.

> **Note:** The application tier is deployed across multiple Availability Zones. The RDS database instance used for this lab is Single-AZ to control lab costs.

## AWS Services & Technologies

- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- EC2 Auto Scaling
- Amazon RDS for MySQL
- Amazon CloudWatch
- Amazon SNS
- Amazon Route 53
- AWS Certificate Manager (ACM)
- AWS Systems Manager (SSM)
- Security Groups
- NAT Gateway
- Internet Gateway
- Linux / Amazon Linux 2023
- Nginx
