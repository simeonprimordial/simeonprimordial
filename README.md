<h1 align="center">☁️ Simeon on the Cloud</h1>

<h3 align="center">Cloud Infrastructure Engineer · AWS · Terraform · Docker · CI/CD</h3>

<p align="center">
  I design, automate, secure, and document production-oriented AWS infrastructure.
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

---

## About Me

I'm **Simeon Siaka**, a cloud infrastructure engineer building hands-on AWS projects around real business and operational requirements.

My work goes beyond creating resources in the AWS console. I focus on:

- designing highly available and fault-tolerant architectures
- provisioning repeatable infrastructure with Terraform
- automating delivery with secure CI/CD workflows
- applying least-privilege IAM and secure secret management
- documenting architecture decisions, validation, and troubleshooting
- balancing reliability, performance, security, and cost

I am currently building an **80-project AWS infrastructure portfolio**. **Seven projects are complete**, with a multi-tenant SaaS platform now in progress.

---

## Featured Engineering Projects

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

Implemented a secure static website delivery and deployment pipeline without long-lived AWS credentials.

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

## Current Build

### [CloudDesk Multi-Tenant SaaS](https://github.com/simeonprimordial/clouddesk-multi-tenant-saas) — Work in Progress

Building the authentication, tenant-isolation, application, and infrastructure foundations for a multi-tenant SaaS platform. The project is being developed through feature branches and pull requests, with architecture and security documentation added alongside implementation.

**Current focus:** Amazon Cognito · OIDC/OAuth 2.0 · tenant isolation · secure session handling · infrastructure automation

---

## Core Stack Demonstrated

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash">
</p>

**AWS services used across projects:** VPC, EC2, Auto Scaling, ALB, NLB, RDS, ECR, S3, CloudFront, IAM, STS, Secrets Manager, Lambda, API Gateway, DynamoDB, SQS, SNS, ElastiCache, and CloudWatch.

---

## How I Approach Projects

1. Start with the business problem and measurable requirements.
2. Design the architecture and document important trade-offs.
3. Provision repeatable infrastructure instead of relying only on console steps.
4. Apply security controls such as private networking, least privilege, OIDC, and managed secrets.
5. Validate the deployment through health checks, failure testing, and observable outcomes.
6. Record troubleshooting lessons so the repository explains both the solution and the engineering process.

---

## Currently Deepening

- multi-tenant SaaS architecture and tenant isolation
- Amazon Cognito authentication and authorization
- container orchestration with Amazon ECS
- CloudWatch monitoring, alarms, and operational dashboards
- automated infrastructure security and quality checks
- Kubernetes, Prometheus, and Grafana as upcoming portfolio areas

---

<p align="center">
  <b>Building secure, scalable, automated, and well-documented cloud infrastructure.</b>
</p>
