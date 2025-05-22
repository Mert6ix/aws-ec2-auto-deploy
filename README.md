# Terraform AWS Web Infrastructure

This project provisions a full AWS infrastructure using Terraform, including:

- VPC (optional)
- Multiple EC2 instances behind an ALB
- Auto-provisioned RDS instance
- S3 bucket for logs or static content
- CI/CD via GitHub Actions

## 🚀 Technologies Used
- AWS
- Terraform
- GitHub Actions
- Bash (user data scripts)

## 📦 Modules
| Module     | Description               |
|------------|---------------------------|
| ec2        | Creates EC2 instances     |
| s3         | Sets up S3 bucket         |
| rds        | Provisions RDS instance   |
| alb        | Configures Load Balancer  |

## 🛠 Getting Started

```bash
terraform init
terraform plan
terraform apply

