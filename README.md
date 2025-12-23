# EKS Prod Infra – Terraform

This repository is a simplified version of how I provision EKS in real projects.  
Sensitive details are removed, but the structure is close to what I use at work.

## What this project does

- Creates a VPC with public and private subnets  
- Provisions an EKS cluster with a managed node group  
- Uses variables so the same code can be reused for dev / stage / prod  

## Tech stack

- AWS EKS  
- Terraform  
- VPC, IAM, Security Groups  

## How to use

terraform init
terraform plan
terraform apply


Use your own AWS account and adjust variables/region before applying.
