# CloudFormation pre-defined template for creating VPC with public and private subnets

This pre-defined template creates a Virtual Private Cloud (VPC) on AWS with public and private subnets and sets up an Internet gateway, route table, and security groups within the VPC.

## Resources
- **VPC:** Creates a Virtual Private Cloud (VPC) with the CIDR block.
- **Internet Gateway:** Creates an Internet Gateway to allow communication between VPC and internet and attaches it to the VPC.
- **Public Subnet:** Creates a public subnet within the VPC with the CIDR block.
- **Private Subnets:** Creates two private subnets within the VPC with CIDR blocks.
- **Route Table:** Creates a route table to allow control of traffic within the VPC and associates it with the public subnet.
- **Security Groups:**: Creates security groups for web servers, HTTPS traffic, and database access.

## How to use the template?
### Prerequisites:
- **AWS account**: You need to create a AWS account to create a VPC.
  
## Steps to deploy
1. Download this template from the repository.
2. Log in to the AWS Management Console.
3. Navigate to the CloudFormation service.
4. Click on "Create stack" and select "With new resources (standard)".
5. Choose "Upload a template file" and upload the template.
6. Click "Next".
7. Provide a stack name and customise parameters (if needed).
8. Click "Next".
9. Click "Create stack".
   
*It may take a few minutes to complete (you can monitor the progress in the CloudFormation console).*

## Outputs
- VPC ID
- Public subnet ID
- Private subnet IDs
- Security group IDs
