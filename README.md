# AWS Scalable Web Application Deployment

## Project Overview

This project demonstrates the deployment of a scalable web application on Amazon Web Services (AWS) using core cloud infrastructure services. The application architecture was designed for high availability, scalability, and load balancing.


## AWS Services Used

* Amazon EC2
* Application Load Balancer (ALB)
* Auto Scaling Group (ASG)
* Amazon CloudWatch
* Security Groups
* Launch Templates
* VPC

## Project Architecture

The architecture includes:

* Multiple EC2 instances running the web application
* Application Load Balancer distributing traffic
* Auto Scaling Group automatically managing instances
* CloudWatch alarms monitoring CPU utilization



## Implementation Steps

### 1. Launch EC2 Instances

* Created EC2 instances using Amazon Linux
* Installed web server packages
* Configured sample web application

### 2. Configure Application Load Balancer

* Created Target Group
* Registered EC2 instances
* Configured ALB listener rules
* Verified load balancing functionality

### 3. Create Launch Template

* Configured AMI
* Selected instance type
* Added security groups
* Configured user data

### 4. Configure Auto Scaling Group

* Attached launch template
* Configured desired capacity
* Configured minimum and maximum instances
* Attached ALB target group

### 5. Configure Scaling Policies

* Created target tracking scaling policy
* Configured CPU utilization threshold

### 6. Configure CloudWatch Monitoring

* Created CloudWatch alarms
* Monitored EC2 CPU usage
* Verified scaling activities


## Features

* High Availability
* Automatic Scaling
* Load Balancing
* Fault Tolerance
* Cloud Monitoring


## Challenges Faced

* Target group health check failures
* Auto Scaling instance health issues
* CloudWatch insufficient data state
* GitHub repository merge conflicts

---

## Outcome

Successfully deployed and configured a scalable web application infrastructure on AWS with monitoring and auto scaling capabilities.


## Future Enhancements

* Route 53 integration
* SSL Certificate configuration
* HTTPS setup
* CI/CD pipeline integration
* RDS database integration


## Author
Jahnavi Nandamudi

Jahnavi Nandamudi
