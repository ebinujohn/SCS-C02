# AWS Services to Study for Security - Specialty Exam

This document outlines the key AWS services and concepts to focus on when preparing for the AWS Certified Security - Specialty exam.

## Table of Contents

1.  [Networking and Content Delivery](#networking-and-content-delivery)
2.  [Compute](#compute)
3.  [Storage](#storage)
4.  [Security, Identity, & Compliance](#security-identity--compliance)
5.  [Management & Governance](#management--governance)
6.  [Analytics](#analytics)
7.  [Application Integration](#application-integration)
8.  [Other](#other)
9.  [General AWS Knowledge](#general-aws-knowledge)
10. [IAM Policies and Access Control](#iam-policies-and-access-control)

## Networking and Content Delivery

- [ ] **VPC Fundamentals**
  - [ ] Subnets, Route Tables, Internet Gateways, NAT Gateways
  - [ ] Security Groups vs. Network ACLs
  - [ ] VPC Flow Logs
  - [ ] VPC Peering
  - [ ] Shared VPC
  - [ ] VPC Origins
- [ ] **VPC Lattice**
- [ ] **VPC DNS Firewall**
- [ ] **VPC Network Firewall**
- [ ] **AWS Network Manager**
- [ ] **AWS Firewall Manager**
- [ ] **VPC VPN** (Site-to-Site and Client VPN)
- [ ] **VPC Verified Access**
- [ ] **Traffic Mirroring**
- [ ] **Transit Gateway**
- [ ] **Gateway Load Balancer Endpoint**
- [ ] **Network Load Balancer** (including TLS termination and security policies)
- [ ] **AWS Network Analyzer**
- [ ] **Route 53**
  - [ ] Profiles
  - [ ] IP-based routing
  - [ ] Traffic flows
  - [ ] Endpoints
  - [ ] Rules
  - [ ] Resolver DNS Firewall
- [ ] **AWS Direct Connect**
- [ ] **AWS Global Accelerator**
- [ ] **API Gateway Resource Policies**

## Compute

- [ ] **EC2 Instance Metadata Service**
- [ ] **Amazon App Runner Services**
- [ ] **AWS Nitro Enclaves**

## Storage

- [ ] **Amazon S3**
  - [ ] Directory buckets
  - [ ] Table buckets
  - [ ] S3 Metadata
  - [ ] Access Control (ACLs, Bucket Policies)
  - [ ] Encryption (SSE-S3, SSE-KMS, SSE-C)
  - [ ] Lifecycle policies
  - [ ] Versioning
  - [ ] Access Points
  - [ ] Object Lambda

## Security, Identity, & Compliance

- [ ] **AWS Identity and Access Management (IAM)**
  - [ ] Users, Groups, Roles
  - [ ] Policies (Identity-based, Resource-based)
  - [ ] Permission Boundaries
  - [ ] Session Policies
  - [ ] How to assume a role
  - [ ] IAM Access Analyzer
- [ ] **AWS Organizations**
  - [ ] Service Control Policies (SCPs)
  - [ ] Resource Control Policies (RCP)
- [ ] **AWS Resource Access Manager (RAM)**
- [ ] **AWS Key Management Service (KMS)**
  - [ ] Customer Managed Keys (CMKs)
  - [ ] AWS Managed Keys
  - [ ] Key Policies
  - [ ] Grants
  - [ ] Key Rotation
  - [ ] Multi-Region Keys
  - [ ] SSE-KMS vs. SSE-S3 vs. other encryption options
- [ ] **AWS Secrets Manager**
- [ ] **AWS Certificate Manager (ACM)**
- [ ] **AWS Directory Service**
- [ ] **AWS Single Sign-On (SSO)**
- [ ] **Amazon GuardDuty**
- [ ] **Amazon Inspector**
- [ ] **Amazon Detective**
- [ ] **AWS Security Hub**
- [ ] **AWS Audit Manager** (including HIPAA and other compliance frameworks)
- [ ] **AWS Shield**
- [ ] **AWS WAF**
- [ ] **AWS Verified Permissions**
- [ ] **AWS Security Data Lake**

## Management & Governance

- [ ] **AWS Well-Architected Framework** (including the Security Pillar)
- [ ] **AWS CloudFormation**
- [ ] **AWS CloudTrail**
- [ ] **CloudWatch**
  - [ ] Logs
  - [ ] Metrics
  - [ ] Alarms
  - [ ] Events
- [ ] **AWS Config**
  - [ ] Rules
  - [ ] Conformance Packs
  - [ ] AWS Config Tower - Controls/Guardrails
- [ ] **AWS Systems Manager (SSM)**
  - [ ] Patch Manager
  - [ ] Parameter Store
  - [ ] Session Manager
  - [ ] Run Command
  - [ ] State Manager
- [ ] **AWS Service Catalog**
  - [ ] AppRegistry
- [ ] **AWS Control Tower**
- [ ] **AWS Backup**
- [ ] **AWS Data Lifecycle Manager**
- [ ] **Policy level guard**
  - [ ] cfn-guard
  - [ ] Terraform Sentinel
  - [ ] tfsec
  - [ ] checkov
  - [ ] pulumi crossguard
  - [ ] terrascan
- [ ] **AWS License Manager**
- [ ] **AWS Trusted Advisor**

## Analytics

- [ ] **Amazon Kinesis**
  - [ ] Kinesis Data Streams
  - [ ] Kinesis Data Firehose
  - [ ] Kinesis Data Analytics
  - [ ] Kinesis Video Streams
  - [ ] Understand the use cases and differences between each.
- [ ] **Amazon OpenSearch Service**
  - [ ] Access Policies
  - [ ] Dashboard Access
  - [ ] Security
  - [ ] Fine-grained access control

## Application Integration

- [ ] **AWS AppSync**
- [ ] **Amazon AppStream**
- [ ] **AWS App Mesh**
- [ ] **Amazon EventBridge**
- [ ] **Amazon Simple Notification Service (SNS)**
- [ ] **Amazon Simple Queue Service (SQS)**

## Other

- [ ] **AWS Solutions Guidance**
- [ ] **AWS Architecture Portal**
- [ ] **AWS Prescriptive Guidance**
- [ ] **AWS Amplify**

## General AWS Knowledge

- [ ] **AWS Overview** (Whitepaper)
- [ ] **AWS Global Infrastructure**
- [ ] **AWS Shared Responsibility Model**
- [ ] **AWS Pricing Model**

## IAM Policies and Access Control

- [ ] **IAM Policies**
  - [ ] **Permission boundaries**
  - [ ] **Organization service control policies (SCP)**
  - [ ] **Session policy**
  - [ ] **Identity based**
  - [ ] **Resource based**
  - [ ] **Organization RCP**
  - [ ] **ACLs**
- [ ] **IAM Policy Evaluation Logic:** [https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_evaluation-logic.html)
- [ ] **IAM Policies Overview:** [https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
- [ ] **Identity-based vs. Resource-based Policies:** [https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_identity-vs-resource.html](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_identity-vs-resource.html)
- [ ] **AWS IAM User Guide**
- [ ] **High-level mind maps for AWS Services** (Focus on security aspects and relationships between services)
- [ ] **Security, Identity, & Compliance on AWS Architecture Center:** [https://aws.amazon.com/architecture/security-identity-compliance/](https://aws.amazon.com/architecture/security-identity-compliance/)
