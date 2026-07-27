# pre-aws-infra

# AWS EKS Two-Tier Application Deployment using Terraform

Deploy a production-ready Amazon Elastic Kubernetes Service (EKS) cluster using Terraform and host a two-tier application on Kubernetes with AWS Application Load Balancer (ALB) Ingress.

This project demonstrates Infrastructure as Code (IaC), Kubernetes orchestration, AWS networking, IAM integration, and production deployment practices commonly used by Platform Engineering and DevOps teams.

---

## Project Overview

This project provisions a complete Kubernetes platform on Amazon EKS using Terraform. The infrastructure is deployed entirely through Infrastructure as Code (IaC), enabling consistent, repeatable, and version-controlled deployments without manual configuration.

After provisioning the infrastructure, a sample two-tier application is deployed to the EKS cluster using Kubernetes manifests. The application is exposed externally through the AWS Load Balancer Controller, which automatically provisions an AWS Application Load Balancer (ALB) based on the Kubernetes Ingress resource.

The project demonstrates the end-to-end workflow of provisioning cloud infrastructure, configuring Kubernetes, deploying applications, and exposing services securely using AWS-native integrations.

### Key Objectives

- Provision AWS infrastructure using Terraform
- Deploy and manage an Amazon EKS cluster
- Configure AWS networking components
- Implement IAM Roles for Service Accounts (IRSA)
- Deploy a containerized application on Kubernetes
- Expose the application using AWS ALB Ingress
- Store Terraform state remotely using Amazon S3 and DynamoDB
- Follow infrastructure organization aligned with production environments

> **Note:** This project focuses on infrastructure provisioning and Kubernetes deployment. The application used is intentionally simple to emphasize the platform engineering aspects of the solution.
