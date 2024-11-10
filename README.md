# Azure Infrastructure Automation: Scripts for Automating Azure Cloud Infrastructure Using IaC Principles

## Introduction
This repository contains a collection of scripts for automating Azure cloud infrastructure deployments using Infrastructure as Code (IaC) principles. The goal is to enable consistent, repeatable, and scalable infrastructure management across Azure environments.

## Technologies Used
- **Bicep**: Azure-native declarative IaC language
- **Terraform**: A popular open-source tool for provisioning cloud infrastructure
- **Azure CLI**: Command-line interface to interact with Azure services

## Folder Structure
- **bicep/**: Bicep scripts for deploying and managing Azure resources
  - **networking/**: Networking resources like Virtual Networks, Subnets
  - **compute/**: Virtual Machines, Scale Sets
  - **storage/**: Storage Accounts, Blob Containers
- **terraform/**: Terraform scripts and modules for Azure infrastructure
  - **modules/**: Reusable Terraform modules for various Azure resources
  - **examples/**: Example configurations for deploying resources
- **scripts/**: Utility scripts for deployment and configuration
  - **deployment/**: Scripts for initial provisioning and setup
  - **configuration/**: Scripts for post-deployment configuration and optimization

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/vashisth20/azure-infrastructure-automation.git
    ```