# Azure Terraform Deployment

## Introduction

This repository contains Terraform code to provision Azure resources, including a resource group and an Azure Key Vault with secrets.

## Prerequisites

Before you begin, ensure you have the following:

- Terraform installed. You can download it from [here](https://www.terraform.io/downloads.html).
- Azure subscription ID and tenant ID.
- Access to an Azure account with sufficient permissions to create resources.
- Variables defined in a `terraform.tfvars` file or passed through command-line arguments.

## Usage

Follow these steps to deploy the Azure resources:

1. Clone this repository to your local machine:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the directory containing the Terraform code:

    ```bash
    cd <repository_directory>
    ```

3. Initialize Terraform:

    ```bash
    terraform init
    ```

4. Review and adjust the variables in the `terraform.tfvars` file according to your requirements.

5. Apply the Terraform configuration:

    ```bash
    terraform apply
    ```

6. Confirm the changes and type `yes` when prompted to deploy the resources.

7. Once the deployment is complete, Terraform will display the output variables, including the Azure Key Vault details.

## Cleaning Up

To remove the deployed Azure resources, run:

```bash
terraform destroy
