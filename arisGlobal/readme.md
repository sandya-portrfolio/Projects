# ArisGlobal – AWS Infrastructure Automation & DevOps Platform

Project Name: ArisGlobal
Company: PKL Limited
Duration: Jun 2016 – Nov 2017

## Project Overview
ArisGlobal is a cloud-based infrastructure automation and DevOps platform designed to streamline application deployment, automate infrastructure provisioning, and improve operational monitoring using AWS cloud services and DevOps practices. The project focused on building scalable CI/CD pipelines, automating cloud infrastructure using Terraform, and implementing centralized monitoring and observability using Datadog. The overall objective was to improve deployment efficiency, reduce manual operational efforts, and ensure reliable application delivery across multiple environments.

## Technologies Used
- AWS
- GitHub
- Jenkins
- Terraform
- Datadog
- Linux
- Shell Scripting
- IAM
- VPC
- EC2
- CloudWatch

## Project Architecture Flow
Developer → GitHub → Jenkins Build Pipeline → Terraform Infrastructure Provisioning → AWS Deployment → Datadog Monitoring & Alerts → Dev/UAT/Prod Environments

## Roles & Responsibilities

### Cloud Infrastructure Management
- Built and managed AWS infrastructure resources to support application deployments and DevOps operations.
- Configured IAM roles, VPC networking, EC2 instances, storage services, and security configurations.
- Automated infrastructure provisioning and environment setup using Terraform.
- Managed cloud resource scaling, deployment environments, and infrastructure maintenance activities.
- Supported secure and scalable cloud operations across environments.

### CI/CD Pipeline Automation
- Designed and implemented CI/CD pipelines using GitHub and Jenkins.
- Automated source code integration, build validation, deployment execution, and release workflows.
- Configured Jenkins jobs and automated deployment triggers based on repository updates.
- Improved deployment speed and reduced manual operational activities using automation.
- Managed deployment approvals, rollback processes, and release coordination activities.

### Infrastructure as Code (IaC)
- Developed reusable Terraform modules for automated AWS infrastructure provisioning.
- Managed environment consistency using Infrastructure as Code practices.
- Automated provisioning of networking, compute, and deployment resources.
- Improved infrastructure reliability and reduced configuration drift across environments.

### Monitoring & Observability
- Integrated Datadog for centralized infrastructure and application monitoring.
- Configured monitoring dashboards, alerting policies, and performance tracking.
- Monitored infrastructure health, deployment activities, and application availability.
- Supported incident troubleshooting and operational issue resolution using monitoring insights.

### Deployment & Production Support
- Managed deployments across Development, UAT, and Production environments.
- Performed deployment troubleshooting, rollback activities, and release validation.
- Supported production release operations and operational stability improvements.
- Coordinated with development and support teams for issue resolution and deployment planning.

## CI/CD Pipeline Workflow

### Step 1 – Source Code Management
Developers committed application code changes into GitHub repositories using version control and branching strategies.

### Step 2 – Continuous Integration
Jenkins automatically triggered build pipelines when code changes were detected. Build validation and automated execution processes were performed.

### Step 3 – Infrastructure Provisioning
Terraform automated provisioning and configuration of AWS infrastructure resources required for deployments.

### Step 4 – Deployment Automation
Applications were deployed into AWS environments using automated deployment workflows and release orchestration processes.

### Step 5 – Monitoring & Alerting
Datadog continuously monitored infrastructure health, application performance, and deployment activities. Alerts and dashboards provided operational visibility and issue tracking.

### Step 6 – Production Support
Deployment logs, infrastructure alerts, and operational reports were monitored to ensure platform stability and reliable application delivery.

## Key Achievements
- Improved deployment automation using GitHub and Jenkins CI/CD workflows.
- Reduced manual infrastructure provisioning efforts using Terraform automation.
- Enhanced infrastructure monitoring and operational visibility using Datadog.
- Improved release reliability, deployment consistency, and cloud operational efficiency.
- Streamlined infrastructure management and deployment support processes.

## Business Impact
The implementation of the ArisGlobal DevOps platform improved cloud infrastructure automation, accelerated deployment workflows, and enhanced monitoring visibility across environments. Infrastructure as Code practices reduced manual provisioning efforts, improved consistency, and increased operational efficiency. Centralized monitoring and CI/CD automation enabled reliable, scalable, and secure application delivery processes across the organization.
