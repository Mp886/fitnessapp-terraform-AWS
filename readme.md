# Fitness Tracker Web App On AWS Using Terraform

This project is a fitness tracker web application that helps users track their workouts, monitor their nutrition, and see their progress. The application is deployed on AWS S3 using Terraform, ensuring an automated and repeatable deployment process.

# Prerequisites
- Terraform installed on your local machine.
- AWS account with appropriate permissions to create and manage S3 buckets and IAM roles.

# Application Development
- Developed a static web application using HTML, CSS, and JavaScript for tracking fitness goals.

# Infrastructure Deployment with Terraform

1) Terraform Configuration:
- Created Terraform scripts to set up and manage the AWS S3 bucket.

2) Terraform Files:
- main.tf: Contains the Terraform configuration for creating the S3 bucket and setting up static website hosting.
- variables.tf: Defines variables used in the Terraform configuration.

# Terraform Commands Used
1) Initialize Terraform:
- Initializes the working directory containing Terraform configuration files. This command downloads the necessary provider plugins.

  Command: terraform init

2) Review Configuration:
- Shows the execution plan, allowing you to see what changes Terraform will make to your infrastructure before applying them.

  command: terraform plan

3) Apply Configuration:
- Applies the changes required to reach the desired state of the configuration. This command creates the S3 bucket and applies the specified settings.

  command: terraform apply

# Summary

This project demonstrates how to deploy a static web application to AWS S3 using Terraform. By managing the infrastructure as code, the deployment process is automated, ensuring consistency and repeatability.
