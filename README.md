# Learning Roadmap to Get Started in Cloud Computing with AWS

Note that AWS has 200+ services, and you don't have to be proficient in all of them. This roadmap covers Cloud and IT fundamentals and a select list of services to help you get started.

---

## 1. Cloud Foundations

### What is Cloud Computing?
Cloud Computing refers to the delivery of computing services over the internet instead of using local servers. It offers reliable, scalable, and inexpensive cloud computing services which include data storage, databases, applications, analytics, machine learning, and even setting up virtual servers. The biggest names providing cloud computing services are Amazon Web Services (AWS), Microsoft Azure, Google Cloud, and others. The main selling point is that you only pay for the services you use, helping you manage your expenses more effectively.

**Resources to learn more:**
- [What is Cloud Computing? - IBM](https://www.ibm.com/topics/cloud-computing)
- [What is Cloud Computing? - AWS](https://aws.amazon.com/what-is-cloud-computing/)

---

### Types of Cloud Computing
IaaS, PaaS, and SaaS are three types of cloud service models:
- **IaaS (Infrastructure as a Service):** Provides users with a resource-based service via virtualization technology, offering computing infrastructure, physical or (more often) virtual machines, and other resources.
- **PaaS (Platform as a Service):** Provides runtime environments for developing, testing, and managing applications, used for software development.
- **SaaS (Software as a Service):** Provides on-demand software accessed via the internet, delivering a complete software solution on a pay-as-you-go basis.

![CC Types](https://github.com/user-attachments/assets/50e75c23-056c-4bcd-b2d6-463a67d52583)

**Resources to learn more:**
- [AWS Types of Cloud Computing](https://aws.amazon.com/types-of-cloud-computing/?nc1=h_ls)
- [Video: Types of Cloud Computing](https://www.youtube.com/watch?v=9CVBohl6w0Q)

---

### Public vs Private vs Hybrid Cloud
- **Public Cloud:** Resources are available to the general public over the internet. Examples: AWS, Google Cloud, Azure.
- **Private Cloud:** Resources are dedicated to a single organization, offering more control and privacy.
- **Hybrid Cloud:** Combines private and public clouds for flexibility, security, and deployment options.

**Resources to learn more:**
- [Public vs Private vs Hybrid Cloud - RedHat](https://www.redhat.com/en/topics/cloud-computing/public-cloud-vs-private-cloud-and-hybrid-cloud)
- [Selecting the Right Cloud for Workloads - AWS](https://docs.aws.amazon.com/whitepapers/latest/public-sector-cloud-transformation/selecting-the-right-cloud-for-workloads-differences-between-public-private-and-hybrid.html)

---

## 2. Networking

### VPC (Virtual Private Cloud)
Amazon VPC lets you launch AWS resources in a logically isolated virtual network. It includes advanced security features like security groups and network access control lists.

**Resources to learn more:**
- [AWS VPC](https://aws.amazon.com/vpc/)
- [Video: Amazon VPC Overview](https://www.youtube.com/watch?v=g2JOHLHh4rI)

---

### Subnets
Subnets are divisions of a VPC’s IP address range. Each subnet must be associated with a route table to control traffic flow.

**Resources to learn more:**
- [Configuring Subnets in AWS VPC](https://docs.aws.amazon.com/vpc/latest/userguide/configure-subnets.html)

---

### Route Tables
Route tables are sets of rules (routes) that determine where network traffic is directed within your VPC.

**Resources to learn more:**
- [AWS VPC Route Table](https://docs.aws.amazon.com/quicksight/latest/user/vpc-route-table.html)

---

### Security Groups
Security groups act as virtual firewalls to control inbound and outbound traffic for your instances.

**Resources to learn more:**
- [AWS VPC Security Groups](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html)

---

### Internet Gateway
An Internet Gateway enables bi-directional routing between a VPC and the internet.

**Resources to learn more:**
- [What is a Network Gateway? - Cisco](https://www.cisco.com/c/en/us/products/routers/what-is-a-network-gateway.html)

---

## 3. Cloud Security

### IAM (Identity and Access Management)
IAM allows you to manage access to AWS services and resources securely. It includes features like granular permissions, identity federation, and multi-factor authentication (MFA).

**Resources to learn more:**
- [AWS IAM Introduction](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)

---

### Data Encryption
Encryption secures data at rest and in transit. AWS Key Management Service (KMS) manages cryptographic keys for encryption.

**Resources to learn more:**
- [AWS KMS Overview](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html)

---

### Compliance and Governance
AWS provides tools for monitoring, auditing, and maintaining compliance, such as AWS Config, CloudTrail, and Security Hub.

**Resources to learn more:**
- [AWS Config Overview](https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html)

---

## 4. Compute Services

### EC2 (Elastic Compute Cloud)
EC2 provides secure, resizable compute capacity for developers. You can choose different instance types optimized for specific workloads.

**Resources to learn more:**
- [Video: Introduction to AWS EC2](https://www.youtube.com/watch?v=eaicwmnSdCs)

---

### Instance Types
AWS offers instance types grouped by use case: General Purpose, Compute Optimized, Memory Optimized, etc.

**Resources to learn more:**
- [AWS EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)

---

### Storage/Volumes
Amazon EBS provides persistent block storage for EC2 instances.

**Resources to learn more:**
- [Amazon EBS Overview](https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html)

---

### Lambda
AWS Lambda runs code in response to events without managing servers. It supports languages like Python, Node.js, and Java.

**Resources to learn more:**
- [AWS Lambda Guide](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

---

## 5. Storage Solutions

### S3 (Simple Storage Service)
Amazon S3 is an object storage service for storing and retrieving data from anywhere.

**Resources to learn more:**
- [AWS S3 User Guide](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)

---

### RDS (Relational Database Service)
RDS simplifies setup, operation, and scaling of relational databases.

**Resources to learn more:**
- [AWS RDS Overview](https://aws.amazon.com/rds/)

---

### DynamoDB
DynamoDB is a managed NoSQL database service offering fast and predictable performance.

**Resources to learn more:**
- [AWS DynamoDB Overview](https://aws.amazon.com/dynamodb/)

---

## 6. High Availability
High availability ensures systems remain operational during failures using redundancy, load balancing, and auto-scaling.

**Resources to learn more:**
- [AWS High Availability Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/real-time-communication-on-aws/high-availability-and-scalability-on-aws.html)

---

## 7. Disaster Recovery
Disaster recovery focuses on restoring IT systems and data after catastrophic events.

![DR](https://github.com/user-attachments/assets/c7289db0-3b67-4a16-8779-2bc694d14924)

**Resources to learn more:**
- [AWS Disaster Recovery Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html)

---

## 8. Serverless Architecture
Serverless architecture allows developers to focus on code without managing infrastructure. AWS Lambda is a key example.

**Resources to learn more:**
- [AWS Serverless Overview](https://aws.amazon.com/serverless/)

---

## 9. CI/CD
CI/CD refers to Continuous Integration and Continuous Delivery/Deployment, streamlining the software development lifecycle.

![CICD](https://www.redhat.com/rhdc/managed-files/styles/wysiwyg_full_width/private/ci-cd-flow-desktop.png.webp?itok=mDEvsSsp)

**Resources to learn more:**
- [CI/CD Explained - YouTube](https://www.youtube.com/watch?v=42UP1fxi2SY)

---

## 10. Infrastructure as Code
Infrastructure as Code (IaC) allows provisioning infrastructure using code. Tools like AWS CloudFormation and Terraform are popular.

**Resources to learn more:**
- [Infrastructure as Code Crash Course](https://www.youtube.com/watch?v=EtEb40LE5zQ&t=573s)
