# Terraform – Assign Variables

This repository shows how to assign variable values using external files and CLI arguments.

## What this covers

- Assigning values via `.tfvars` files
- Overriding variables from the command line

## Key idea

Variable values are not entered manually in the terminal, but assigned in a seperate .tfvars file. Where there are several tfvars file, it has to be specified when running the code. 


## How to apply variables

Example ofsing a variable file:

```bash
terraform apply -var-file=prod.tfvars

## How to run
```bash
terraform init
terraform plan
terraform apply

### Destroy resources when finished

```
terraform destroy
```