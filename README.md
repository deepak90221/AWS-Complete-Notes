# ☁️ AWS & Cloud Computing Learning Roadmap

This repository documents my journey of learning **Cloud Computing and Amazon Web Services (AWS)** through structured notes, hands-on labs, practical implementations, and real-world projects.

The goal is to understand AWS from **fundamentals to advanced cloud architecture** and learn how to build, deploy, secure, monitor, and scale applications in the cloud.

---

## 🗺️ AWS Learning Roadmap

```text
                         AWS & CLOUD COMPUTING
                                  │
        ┌─────────────────────────┴─────────────────────────┐
        │                                                   │
   CLOUD FUNDAMENTALS                                AWS FUNDAMENTALS
        │                                                   │
        ├── What is Cloud Computing                         ├── AWS Global Infrastructure
        ├── IaaS / PaaS / SaaS                              ├── Regions
        ├── Public / Private / Hybrid Cloud                 ├── Availability Zones
        ├── Scalability                                     └── Edge Locations
        ├── Elasticity
        └── Pay-as-you-go
                                  │
                                  ▼
                         IDENTITY & SECURITY
                                  │
                         ├── IAM
                         ├── Users
                         ├── Groups
                         ├── Roles
                         ├── Policies
                         ├── MFA
                         └── Least Privilege
                                  │
                                  ▼
                          COMPUTE SERVICES
                                  │
                         ├── EC2
                         ├── AMIs
                         ├── EBS
                         ├── Auto Scaling
                         ├── Load Balancer
                         ├── Lambda
                         └── Elastic Beanstalk
                                  │
                                  ▼
                           STORAGE SERVICES
                                  │
                         ├── S3
                         ├── EBS
                         ├── EFS
                         ├── S3 Storage Classes
                         ├── Versioning
                         └── Lifecycle Policies
                                  │
                                  ▼
                          DATABASE SERVICES
                                  │
                         ├── RDS
                         ├── Aurora
                         ├── DynamoDB
                         ├── ElastiCache
                         └── Database Backups
                                  │
                                  ▼
                           NETWORKING
                                  │
                         ├── VPC
                         ├── Subnets
                         ├── Route Tables
                         ├── Internet Gateway
                         ├── NAT Gateway
                         ├── Security Groups
                         ├── NACLs
                         ├── DNS / Route 53
                         └── VPC Peering
                                  │
                                  ▼
                       CONTAINERS & DEPLOYMENT
                                  │
                         ├── Docker
                         ├── ECR
                         ├── ECS
                         ├── Fargate
                         ├── EKS
                         └── Kubernetes Basics
                                  │
                                  ▼
                            SERVERLESS
                                  │
                         ├── Lambda
                         ├── API Gateway
                         ├── EventBridge
                         ├── SQS
                         └── SNS
                                  │
                                  ▼
                         MONITORING & LOGGING
                                  │
                         ├── CloudWatch
                         ├── CloudTrail
                         ├── Logs
                         ├── Metrics
                         └── Alarms
                                  │
                                  ▼
                             CI/CD
                                  │
                         ├── Git
                         ├── GitHub
                         ├── CI/CD Concepts
                         ├── GitHub Actions
                         └── Basic Jenkins
                                  │
                                  ▼
                          AI / ML ON AWS
                                  │
                         ├── SageMaker
                         ├── Bedrock
                         ├── S3 for Datasets
                         ├── Model Deployment
                         └── ML Application Deployment
                                  │
                                  ▼
                       SECURITY & BEST PRACTICES
                                  │
                         ├── KMS
                         ├── Secrets Manager
                         ├── Parameter Store
                         ├── IAM Best Practices
                         └── Security Best Practices
                                  │
                                  ▼
                      ARCHITECTURE & PROJECTS
                                  │
                         ├── High Availability
                         ├── Scalability
                         ├── Fault Tolerance
                         ├── Cost Optimization
                         ├── Well-Architected Framework
                         └── Real-World Projects
```

---

# 📚 Phase 1 — Cloud Computing Fundamentals

Before going deep into AWS, understand the fundamentals of cloud computing.

### Topics

* What is Cloud Computing?
* Why Cloud Computing?
* Traditional IT vs Cloud
* IaaS
* PaaS
* SaaS
* Public Cloud
* Private Cloud
* Hybrid Cloud
* Scalability
* Elasticity
* Availability
* Fault Tolerance
* High Availability
* Pay-as-you-go model
* CapEx vs OpEx

---

# ☁️ Phase 2 — AWS Fundamentals

Understand how AWS works globally.

### Topics

* What is AWS?
* AWS Management Console
* AWS CLI
* AWS SDK
* AWS Regions
* Availability Zones
* Edge Locations
* AWS Global Infrastructure
* AWS service categories
* AWS pricing basics
* AWS Free Tier
* AWS Billing & Cost Management

---

# 🔐 Phase 3 — Identity & Security

### IAM

Learn:

* IAM Users
* IAM Groups
* IAM Roles
* IAM Policies
* Managed Policies
* Custom Policies
* Authentication
* Authorization
* MFA
* Access Keys
* Least Privilege
* Root User
* IAM Policy Evaluation

### Security Services

Later learn:

* AWS KMS
* AWS Secrets Manager
* Systems Manager Parameter Store
* AWS CloudTrail
* AWS WAF
* AWS Shield

---

# 🖥️ Phase 4 — Compute

### Amazon EC2

Learn:

* EC2 instances
* Instance types
* AMIs
* Key pairs
* EBS
* Security Groups
* User Data
* Elastic IP
* Instance lifecycle
* SSH
* Windows/Linux instances

### Scaling

* Auto Scaling
* Launch Templates
* Load Balancers
* Target Groups
* Health Checks

### Other Compute

* Lambda
* Elastic Beanstalk

---

# 💾 Phase 5 — Storage

### Amazon S3

Learn:

* Buckets
* Objects
* Object keys
* Storage classes
* Versioning
* Lifecycle rules
* Bucket policies
* Encryption
* Static website hosting
* Multipart upload
* Presigned URLs

### Other Storage

* EBS
* EFS
* S3 Glacier

---

# 🗄️ Phase 6 — Databases

### RDS

Learn:

* MySQL
* PostgreSQL
* MariaDB
* SQL Server
* Oracle
* Automated backups
* Snapshots
* Multi-AZ
* Read Replicas

### NoSQL

* DynamoDB
* Tables
* Items
* Partition Keys
* Sort Keys
* Query vs Scan

### Other

* Aurora
* ElastiCache

---

# 🌐 Phase 7 — Networking

This is one of the most important AWS areas.

### VPC

Learn:

* VPC
* CIDR
* Subnets
* Public Subnets
* Private Subnets
* Route Tables
* Internet Gateway
* NAT Gateway
* Security Groups
* Network ACLs

### Advanced Networking

* VPC Peering
* Transit Gateway
* VPC Endpoints
* Elastic IP
* DNS
* Route 53

Understand this architecture:

```text
Internet
   ↓
Internet Gateway
   ↓
Public Subnet
   ↓
Load Balancer
   ↓
Private Subnet
   ↓
Application
   ↓
Database
```

---

# 🐳 Phase 8 — Containers

Since modern applications commonly use containers:

### Docker

Learn:

* Images
* Containers
* Dockerfile
* Docker Hub
* Volumes
* Networks
* Docker Compose
* Container ports

### AWS Containers

* ECR
* ECS
* Fargate
* ECS Task Definitions
* ECS Services
* ECS Clusters
* Load Balancer + ECS

### Later

* Kubernetes basics
* Amazon EKS

You don't need to go extremely deep into Kubernetes if your goal remains **AI/ML + AWS rather than DevOps**.

---

# ⚡ Phase 9 — Serverless & Application Integration

### Lambda

Learn:

* Functions
* Runtime
* Handler
* Environment Variables
* Layers
* Permissions
* IAM Roles
* Triggers
* Monitoring

### API Gateway

Learn:

* REST APIs
* HTTP APIs
* Lambda integration
* API endpoints

### Messaging

* SQS
* SNS
* EventBridge

Understand:

```text
S3
 ↓
Event
 ↓
Lambda
 ↓
Process Data
 ↓
DynamoDB
```

---

# 📊 Phase 10 — Monitoring & Logging

### CloudWatch

Learn:

* Metrics
* Logs
* Log Groups
* Log Streams
* Alarms
* Dashboards
* Application monitoring

### CloudTrail

Learn:

* API activity
* AWS account auditing
* Event history

---

# 🔄 Phase 11 — Git & CI/CD

Learn enough CI/CD to deploy your applications automatically.

### Git

* Repository
* Branches
* Commit
* Push
* Pull
* Merge
* Pull Request

### CI/CD

Understand:

```text
Code
 ↓
Build
 ↓
Test
 ↓
Package
 ↓
Deploy
```

### Tools

* GitHub Actions ⭐
* Basic Jenkins knowledge

You don't need to become a Jenkins/DevOps specialist.

---

# 🤖 Phase 12 — AI/ML on AWS

This is particularly important for my AI/ML-focused learning path.

### Amazon SageMaker

Learn:

* Training
* Datasets
* Model artifacts
* Endpoints
* Inference
* Model deployment
* Monitoring

### Amazon Bedrock

Learn:

* Foundation models
* Generative AI
* Model APIs
* Prompt-based applications
* Knowledge bases / RAG concepts

### ML Application Architecture

```text
Dataset
   ↓
S3
   ↓
Training
   ↓
ML Model
   ↓
SageMaker
   ↓
API
   ↓
Application
```

---

# 🔒 Phase 13 — Advanced Security

Learn:

* IAM best practices
* KMS
* Encryption
* Secrets Manager
* Parameter Store
* CloudTrail
* WAF
* Shield
* Security Groups
* Network ACLs
* Private subnets
* VPC endpoints

---

# 🏗️ Phase 14 — AWS Architecture

Learn how to combine services rather than learning services individually.

### Important concepts

* High Availability
* Fault Tolerance
* Scalability
* Reliability
* Disaster Recovery
* Backup
* Security
* Performance
* Cost Optimization

### AWS Well-Architected Framework

Understand the six pillars:

1. Operational Excellence
2. Security
3. Reliability
4. Performance Efficiency
5. Cost Optimization
6. Sustainability

---

# 💰 Phase 15 — Cost Management

Learn:

* AWS Pricing
* Free Tier
* Billing Dashboard
* Cost Explorer
* Budgets
* Cost allocation
* Right-sizing
* Stopping unused resources
* Storage lifecycle policies

This is important because AWS resources can generate charges even when you're experimenting.

---

# 🧪 Phase 16 — Hands-on Labs

For every major service:

```text
Learn Concept
     ↓
Read Notes
     ↓
Perform Lab
     ↓
Take Screenshots
     ↓
Document Steps
     ↓
Understand Troubleshooting
```

Example:

```text
IAM
 ↓
Create User
 ↓
Create Group
 ↓
Attach Policy
 ↓
Test Permissions
 ↓
Document Lab
```

---

# 🚀 Phase 17 — Real-World Projects

Build projects that combine multiple AWS services.

### Project 1 — Static Website

```text
HTML/CSS/JS
     ↓
S3
     ↓
CloudFront
     ↓
Route 53
```

### Project 2 — Full-Stack Application

```text
React
 ↓
Load Balancer
 ↓
ECS/Fargate
 ↓
RDS
```

### Project 3 — Serverless Application

```text
React
 ↓
API Gateway
 ↓
Lambda
 ↓
DynamoDB
```

### Project 4 — AI/ML Application

```text
React
 ↓
API
 ↓
ECS / Lambda
 ↓
ML Model
 ↓
S3 / SageMaker
```

### Project 5 — Automated Deployment

```text
GitHub
   ↓
GitHub Actions
   ↓
Docker
   ↓
ECR
   ↓
ECS/Fargate
   ↓
AWS
```

---

# 📈 Learning Progress

## Cloud Fundamentals

* [ ] Cloud Computing
* [ ] IaaS / PaaS / SaaS
* [ ] Public / Private / Hybrid Cloud
* [ ] Scalability & Elasticity
* [ ] Availability & Fault Tolerance

## AWS Fundamentals

* [ ] AWS Global Infrastructure
* [ ] Regions
* [ ] Availability Zones
* [ ] AWS CLI
* [ ] Billing & Cost Management

## Security

* [ ] IAM
* [ ] Users
* [ ] Groups
* [ ] Roles
* [ ] Policies
* [ ] MFA
* [ ] KMS
* [ ] Secrets Manager

## Compute

* [ ] EC2
* [ ] AMI
* [ ] EBS
* [ ] Auto Scaling
* [ ] Load Balancer
* [ ] Lambda
* [ ] Elastic Beanstalk

## Storage

* [ ] S3
* [ ] Storage Classes
* [ ] Versioning
* [ ] Lifecycle
* [ ] EBS
* [ ] EFS

## Databases

* [ ] RDS
* [ ] Aurora
* [ ] DynamoDB
* [ ] ElastiCache

## Networking

* [ ] VPC
* [ ] Subnets
* [ ] Route Tables
* [ ] Internet Gateway
* [ ] NAT Gateway
* [ ] Security Groups
* [ ] NACL
* [ ] Route 53
* [ ] VPC Endpoints

## Containers

* [ ] Docker
* [ ] ECR
* [ ] ECS
* [ ] Fargate
* [ ] Load Balancer + ECS
* [ ] Kubernetes Basics
* [ ] EKS

## Serverless

* [ ] Lambda
* [ ] API Gateway
* [ ] SQS
* [ ] SNS
* [ ] EventBridge

## Monitoring

* [ ] CloudWatch
* [ ] CloudTrail
* [ ] Logs
* [ ] Metrics
* [ ] Alarms

## CI/CD

* [ ] Git
* [ ] GitHub
* [ ] CI/CD Concepts
* [ ] GitHub Actions
* [ ] Basic Jenkins

## AI/ML

* [ ] SageMaker
* [ ] Bedrock
* [ ] Model Deployment
* [ ] ML APIs
* [ ] AI/ML Architecture

## Architecture

* [ ] High Availability
* [ ] Scalability
* [ ] Fault Tolerance
* [ ] Disaster Recovery
* [ ] Cost Optimization
* [ ] Well-Architected Framework

---

# 🎯 Final Goal

By completing this roadmap, the goal is to be able to:

> **Build an application, containerize it, deploy it on AWS, connect it to databases/storage, secure it with IAM, monitor it with CloudWatch, automate deployment using CI/CD, and deploy AI/ML applications using AWS services.**

