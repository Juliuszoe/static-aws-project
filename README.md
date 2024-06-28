# Terraform Static Website

This project sets up a static website using AWS services managed by Terraform.

## Modules
- **S3 Bucket**: Hosts the static website files.
- **CloudFront**: Distributes the website globally.
- **Route 53**: Manages the DNS for the domain.
- **IAM**: Manages access permissions.
- **API Gateway**: Provides API endpoints (example setup).

## Setup
1. Configure AWS credentials.
2. Initialize Terraform.
   ```sh
   terraform init
