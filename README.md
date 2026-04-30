# Terraform Infrastructure – Personal Showcase Site

This repository contains the Infrastructure as Code (IaC) used to provision and manage the cloud resources for my personal showcase website using Terraform.

The project demonstrates best practices for building, deploying, and maintaining scalable infrastructure in Microsoft Azure.

---

## Overview

This Terraform project is designed to:

- Provision all required Azure infrastructure for a production-ready website  
- Demonstrate modular, reusable Terraform code  
- Enable consistent and repeatable deployments  
- Showcase DevOps and cloud engineering practices  

---

## Technologies Used

- **Infrastructure as Code:** Terraform  
- **Cloud Provider:** Microsoft Azure  
- **CI/CD:** Azure DevOps / GitHub Actions / Bitbucket Pipelines  
- **Hosting:** Azure App Service / Static Web Apps  
- **Networking & Security:** Azure Front Door / NSGs / Private Endpoints *(if applicable)*  

---

## Project Structure

.
├── main.tf              # Core infrastructure definitions
├── variables.tf         # Input variables
├── outputs.tf           # Output values
├── providers.tf         # Provider configuration
├── terraform.tfvars     # Environment-specific values (not committed)
├── modules/             # Reusable Terraform modules
└── environments/        # Environment-specific configurations (e.g. dev/prod)

---

## Prerequisites

- Terraform (>= 1.x)
- Azure CLI
- An active Azure subscription

Login to Azure before running Terraform:

```bash
az login