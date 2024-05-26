# User documentation

## Package overview:
This package contains four (4) AWS CloudFormation templates for deploying VPCs, EC2 instances, RDS databases, and associating Elastic IPs on the Amazon Web Services (AWS) platform.

## How to use this package?
### Prerequisites:
- **AWS account**: You need to create a AWS account to deploy the package templates.
  
### Please follow this deployment order: 
1. VPC
2. Elastic IP
3. RDS database
4. EC2 instance

## Steps to run the containerised application:

1. **Select the CloudFormation template with the resource you want to deploy:**
   - create_vpc_template.yaml: Creates a VPC with public and private subnets, along with security groups
   - create_eip_template.yaml: Creates an Elastic IP
   - create_rds_template.yaml: Creates an RDS database with MySQL
   - create_ec2_template.yaml: Creates an EC2 instance within the VPC and attaches it to the Elastic IP

2. **Deploy the selected template:**
   - Download this template from the repository.
   - Log in to the AWS Management Console.
   - Navigate to the CloudFormation service.
   - Click on "Create stack" and select "With new resources (standard)".
   - Choose "Upload a template file" and upload the template.
   - Click "Next".
   - Provide a stack name and customise parameters (if needed).
   - Click "Next".
   - Click "Create stack".

*It may take a few minutes to complete (you can monitor the progress in the CloudFormation console).*
