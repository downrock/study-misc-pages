# AWS Solutions Architect Exam Guide

Welcome to the AWS Solutions Architect Exam Guide! This resource will help you navigate through the four main exam content areas. Click on a topic to access detailed information.

---

## Exam Content Areas

### [Design Secure Architectures](#design-secure-architectures)
Topics Covered:
- AWS IAM (Identity and Access Management)
- AWS CloudTrail
- AWS Shield and WAF
- Security Groups vs. NACLs
- AWS KMS (Key Management Service)

---

### [Design Resilient Architectures](#design-resilient-architectures)
Topics Covered:
- Multi-Tier Application Architecture
- Amazon EFS (Elastic File System)
- Amazon DynamoDB (Global Tables, Backups, and Replication)
- Amazon Aurora (Global Database and Disaster Recovery)
- Elastic Load Balancer (Stickiness and Session Affinity)

---

### [Design High-Performing Architectures](#design-high-performing-architectures)
Topics Covered:
- AWS Lambda (Use Cases: File Processing, Stream Processing, IoT Backends, Web Applications)
- Amazon SQS (FIFO Queues, SNS Integration)
- Amazon Redshift (Petabyte-scale Analytics)
- Elastic Fabric Adapter (HPC and ML Applications)
- Amazon CloudFront (Distributions and Security Dashboard)

---

### [Design Cost-Optimized Architectures](#design-cost-optimized-architectures)
Topics Covered:
- AWS Budgets
- AWS Savings Plans (Compute and EC2 Instance Savings Plans)
- NAT Gateway vs. Transit Gateway
- Amazon S3 (Versioning and Storage Classes)
- AWS CloudFormation (Infrastructure-as-Code Efficiency)

---

## Quick Links
- [AWS Solutions Architect Study Guide](index.md)
- [AWS Official Exam Resources](https://aws.amazon.com/certification/certified-solutions-architect-associate/)

---

Click on the respective section headings above to dive deeper into each exam content area. If there are additional topics you'd like covered, let me know, and we can add them!

# AWS Solutions Architect Study Guide

Welcome to your AWS Solutions Architect study guide. This resource provides comprehensive insights into AWS services and architectures to support your preparation.

---

## Multi-Tier Application Architecture
- **Benefits:** Improved security, performance, scalability, fine-grained management, maintenance, and availability. Promotes decoupling.
- **Architecture Layers:**
  - **Data Access Tier (Bottom Tier):** Database Servers, Systems.
  - **Business Logic Tier (Middle Tier):** Application tier, app servers.
  - **Presentation Tier (Top Tier):** Frontend, client computer, Web server.

---

## AWS IAM (Identity and Access Management)
- **IAM Policy Components:**
  - Sid, Effect, Principal, Action, Resource, and Condition.
  - Version is part of the IAM Policy, not the statement.

---

## Billing and Cost Management

### AWS Budgets
- Set custom budgets with alerts for threshold breaches. The hub for tracking and inspecting your budgets.

### AWS Service Plans
- Flexible pricing models for 1- or 3-year terms.
  - **Types:**
    - Compute Savings Plans
    - EC2 Instance Savings Plans

---

## Management and Governance

### AWS CloudTrail
- Enables governance, compliance, and operational auditing.
- **CloudTrail Insights:** Detect unusual API activity (retained for 90 days).
- **CloudTrail Lake:** Immutably stores audit-worthy events.

### AWS CloudWatch
- Application Performance Monitoring (APM) tool.
- Provides observability, alarms, and resource optimization.
- Features Application Insights for detection and resolution of issues in apps, databases, and workloads.

---

## Key AWS Services

### AWS Lambda
- Run code without provisioning servers.
- **Use Cases:**
  - File Processing (via Amazon S3).
  - Stream Processing (via Amazon Kinesis).
  - Scalable Web and IoT Backends.
  - Mobile Backends (via Amazon API Gateway and AWS Amplify).

### AWS CloudFormation
- Foundational Infrastructure-as-Code service with YAML or JSON templates.

### Amazon SQS (Simple Queue Service)
- Benefits: Security, durability, availability, scalability, and reliability.
- **Producers > SQS Queue > Consumers Workflow:**
  - **Producers:** Send messages.
  - **Queues:** Store messages awaiting processing.
  - **Consumers:** Process messages.

---

## Networking Services

### VPC Peering
- Connect VPCs across accounts or regions without gateways or VPN.

### NAT Gateway vs. Transit Gateway
- **NAT Gateway:** Secure connections for private subnets to external services.
- **Transit Gateway:** Hub for interconnecting VPCs and on-premises networks.

### Elastic Load Balancing
- Distributes incoming traffic across EC2 instances, containers, and IP addresses.

---

## Additional AWS Services
- **Amazon EFS (Elastic File System):** Scalable file storage for EC2 instances.
- **Amazon Redshift:** Petabyte-scale, serverless data warehouse for analytics.
- **Amazon DynamoDB:** High-performance NoSQL database with continuous backups and global table replication.
- **AWS Shield and WAF:** Security features for applications.

---

## Specialized AWS Tools
- **Amazon Textract:** Extracts data from documents.
- **Amazon Translate:** Enables real-time translations.
- **Amazon Bedrock:** Managed environment for building knowledge bases using foundation models.
