# Large-Scale-Data-Engineering-AWS


This repository contains the implementation of two large-scale data engineering projects using AWS services:

1. **MyTravel Website Architecture**: A scalable, highly available, and low-latency architecture for an international travel forum using AWS services like S3, DynamoDB, Lambda, CloudFront, and Route 53.
2. **WordFreq Application**: A text processing application that analyzes text files to identify the top 10 most frequently used words. The application uses EC2, SQS, DynamoDB, and auto-scaling to handle varying workloads efficiently.

## Project Details

### MyTravel Website Architecture
- **Services Used**: Amazon S3, DynamoDB, Lambda, CloudFront, Route 53, SES, S3 Glacier, CloudWatch.
- **Features**: High availability, low latency, global content delivery, automated backups, and email notifications.
- **Architecture Diagram**: [MyTravel_Architecture/architecture_diagram.png](MyTravel_Architecture/architecture_diagram.png)

### WordFreq Application
- **Services Used**: EC2, SQS, DynamoDB, Lambda, CloudWatch, Auto Scaling.
- **Features**: Auto-scaling based on SQS queue length, cost optimization using EC2 Spot Instances, and DynamoDB On-Demand.
- **Optimizations**: Improved resilience using ELB, multi-region replication, and enhanced security using IAM roles, VPC, and AWS WAF.

## Repository Structure
- **MyTravel_Architecture**: Contains the architecture diagram, description, and AWS services used.
- **WordFreq_Application**: Includes setup instructions, auto-scaling configuration, load testing results, and optimized architecture.
- **scripts**: Contains Lambda functions and auto-scaling scripts.
- **screenshots**: Screenshots of AWS resources like EC2 instances, S3 buckets, SQS queues, and DynamoDB tables.

## How to Use
1. Clone the repository.
2. Follow the instructions in the respective folders to set up the MyTravel architecture or the WordFreq application.
3. Refer to the screenshots and scripts for implementation details.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
