<h1 align="center">☁️ Simeon on the Cloud</h1>

<h3 align="center">Cloud Infrastructure Engineer · AWS · Terraform · AWS SAM · Docker · CI/CD</h3>

<p align="center">
  I design, automate, secure, test, and document production-oriented cloud infrastructure.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/simeon-siaka-8a8367312/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:simeonvault@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://simeonprimordial.github.io/SimeonOnTheCloudSpace/">
    <img src="https://img.shields.io/badge/Portfolio-F2A93B?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
</p>

<p align="center">
  <a href="https://github.com/simeonprimordial/AWS80ProjectsChallenge">
    <img src="https://img.shields.io/badge/AWS_80_Projects-8%20Completed-success?style=flat-square" alt="AWS 80 Projects Challenge: 8 completed">
  </a>
  <a href="https://github.com/simeonprimordial/clouddesk-multi-tenant-saas">
    <img src="https://img.shields.io/badge/Latest_Project-CloudDesk_SaaS-2088FF?style=flat-square" alt="Latest project: CloudDesk SaaS">
  </a>
</p>

---

## About Me

I'm **Simeon Siaka**, a cloud infrastructure engineer building hands-on AWS systems around real business and operational requirements.

My work goes beyond creating resources in the AWS console. I focus on:

- designing highly available, scalable, and fault-tolerant architectures
- provisioning repeatable infrastructure with Terraform and AWS SAM
- automating testing and deployment with secure CI/CD workflows
- applying private networking, least-privilege IAM, OIDC, and managed secrets
- implementing monitoring, alarms, dashboards, and operational logging
- documenting architecture decisions, validation, troubleshooting, and lessons learned
- balancing reliability, security, performance, cost, and operational simplicity

I am building an **80-project AWS infrastructure portfolio**. **Eight projects are complete**, including a serverless multi-tenant SaaS backend with authentication, tenant-level authorization, PostgreSQL persistence, automated testing, CI/CD, and observability.

---

## Featured Engineering Projects

### [CloudDesk Multi-Tenant SaaS](https://github.com/simeonprimordial/clouddesk-multi-tenant-saas)

Built a production-inspired serverless backend that allows multiple organizations to securely share one application while maintaining tenant-level data isolation and role-based access control.

**Engineering evidence:**

- implemented Amazon Cognito registration, authentication, JWT authorization, and post-confirmation user provisioning
- modeled users, tenants, and memberships in Amazon RDS for PostgreSQL
- enforced tenant-level `owner`, `admin`, and `member` permissions through reusable authorization guards
- protected database credentials with AWS Secrets Manager and private VPC endpoint access
- deployed Lambda functions and API Gateway HTTP APIs through AWS SAM and CloudFormation
- used GitHub Actions with AWS OIDC and STS instead of long-lived deployment credentials
- added Black, isort, Ruff, pytest, coverage checks, SAM validation, and automated builds
- implemented structured logging, CloudWatch alarms, an operational dashboard, and SNS notifications
- documented the architecture, API, deployment, security, monitoring, testing, cost, performance, decisions, and troubleshooting

**Stack:** AWS · Python · AWS SAM · Lambda · API Gateway · Cognito · PostgreSQL · Secrets Manager · CloudWatch · SNS · GitHub Actions · OIDC

---

### [LogiHaul — Pan-Nigeria Logistics Platform](https://github.com/simeonprimordial/logihaul-reference-architecture)

Designed a serverless-first, multi-AZ logistics architecture capable of absorbing a modeled **50× traffic spike** without manual intervention.

**Engineering evidence:**

- separated spike-prone order intake from the EC2 web tier
- used API Gateway, Lambda, DynamoDB, SQS, and SNS for asynchronous order processing
- documented DynamoDB access patterns before schema design
- defined reserved Lambda concurrency and SQS buffering behavior
- selected RDS MySQL Multi-AZ and Redis according to workload and cost requirements
- documented observability, failure testing, and regional resilience decisions

**Stack:** AWS · Lambda · API Gateway · DynamoDB · SQS · SNS · RDS · ElastiCache · EC2 · Auto Scaling · CloudWatch

---

### [FinTrust Customer Portal](https://github.com/simeonprimordial/fintrust-customer-portal)

Built a production-oriented three-tier customer management application using Terraform and Docker.

**Engineering evidence:**

- provisioned private application and database subnets
- deployed Docker images from Amazon ECR to an Auto Scaling Group
- routed traffic through an Application Load Balancer with health checks
- integrated Flask and SQLAlchemy with Amazon RDS MySQL
- replaced hardcoded credentials with AWS Secrets Manager
- added automated Terraform, Bash, and Python validation checks
- documented architecture, deployment flow, engineering decisions, and troubleshooting

**Stack:** AWS · Terraform · Docker · ECR · ALB · Auto Scaling · RDS · Secrets Manager · Flask

---

### [NovaTech Serverless Website](https://github.com/simeonprimordial/novatech-serverless-website)

Implemented secure static website delivery and an automated deployment pipeline without long-lived AWS credentials.

**Engineering evidence:**

- kept the S3 origin private behind CloudFront Origin Access Control
- automated deployments and CloudFront invalidation with GitHub Actions
- used GitHub OIDC and AWS STS for short-lived deployment credentials
- scoped the deployment role to the required S3 bucket actions
- documented security, cost, Well-Architected alignment, and operational decisions

**Stack:** Amazon S3 · CloudFront · IAM · AWS STS · GitHub Actions · OIDC

---

### [Highly Available Web Application with Terraform](https://github.com/simeonprimordial/highly-available-web-app-terraform)

Provisioned a repeatable AWS web tier that distributes traffic and automatically replaces unhealthy instances.

**Engineering evidence:**

- used Terraform data sources, variables, outputs, and resource references
- configured an ALB, target group, launch template, and Auto Scaling Group
- restricted instance traffic to requests originating from the load balancer
- automated Apache installation with EC2 user data
- validated target health, traffic distribution, and instance replacement

**Stack:** Terraform · EC2 · ALB · Auto Scaling · Linux · Bash

---

## AWS 80 Projects Challenge

The [AWS 80 Projects Challenge](https://github.com/simeonprimordial/AWS80ProjectsChallenge) is the central index for my growing cloud engineering portfolio.

```text
Progress: [########........................................................................] 8 / 80
```

Each substantial project aims to demonstrate:

- a defined business or operational problem
- documented architecture and engineering trade-offs
- secure and repeatable infrastructure deployment
- validation, testing, and failure-oriented troubleshooting
- monitoring, cost awareness, and operational readiness
- clear documentation that explains both the result and the engineering process

---

## Core Stack Demonstrated

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/AWS_SAM-CB2C30?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS SAM">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash">
</p>

**AWS services used across projects:** VPC, EC2, Auto Scaling, ALB, NLB, Lambda, API Gateway, Cognito, RDS, DynamoDB, ElastiCache, ECR, S3, CloudFront, IAM, STS, Secrets Manager, SQS, SNS, CloudWatch, and AWS Systems Manager.

---

## How I Approach Projects

1. Start with the business problem and measurable requirements.
2. Design the architecture and document important trade-offs.
3. Provision repeatable infrastructure instead of relying only on console steps.
4. Apply security controls such as private networking, least privilege, OIDC, managed secrets, and tenant-aware authorization.
5. Automate formatting, static analysis, tests, infrastructure validation, builds, and deployments.
6. Validate the system through health checks, permission tests, failure scenarios, logs, metrics, and alarms.
7. Record decisions and troubleshooting lessons so the repository explains both the solution and the engineering process.

---

## Currently Deepening

- AWS and Azure infrastructure administration
- serverless and event-driven architecture
- multi-tenant SaaS security and authorization
- container orchestration with Amazon ECS
- CloudWatch monitoring, alarms, and operational dashboards
- secure multi-environment CI/CD and infrastructure quality checks
- Kubernetes, Prometheus, and Grafana as upcoming portfolio areas

---

<p align="center">
  <b>Building secure, scalable, automated, observable, and well-documented cloud infrastructure.</b>
</p>
