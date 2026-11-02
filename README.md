# AWS Cloud Monitoring Lab

## Project Overview
A hands-on AWS project focused on cloud resource monitoring, cost management, and infrastructure visibility using Amazon CloudWatch.

## AWS Services Used
- Amazon CloudWatch
- AWS Budgets
- AWS Usage Metrics

## Project Implementation

### 1. AWS Cost Management
- Created a monthly AWS cost budget.
- Configured a $5 USD budget.
- Configured actual spending alerts at 85% and 100%.
- Configured a forecasted spending alert at 100%.

### 2. CloudWatch Dashboard
Created a dashboard named `AWS-Cloud-Monitoring-Lab` in Asia Pacific (Singapore).

### 3. Monitoring Metrics
Added three AWS Usage metrics:

| Metric | Description |
|---|---|
| RulesPerSecurityGroup | Security group rule usage |
| IPv4CidrBlocksPerVPC | IPv4 CIDR block usage |
| RoutesPerRouteTable | Route table route usage |

## Skills Demonstrated
- AWS Management Console
- Amazon CloudWatch
- AWS Budgets
- Cloud resource monitoring
- Cost awareness
- Cloud infrastructure documentation

## Project Architecture
AWS Resources → AWS Usage Metrics → CloudWatch Dashboard

## Security Practices
- Monitored AWS spending through AWS Budgets.
- Avoided exposing AWS credentials.
- Used existing AWS resources for initial monitoring.
- Reviewed resource usage before deploying additional infrastructure.

## Project Status
In Progress

## Author
Sujendran
