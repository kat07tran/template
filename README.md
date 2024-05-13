# CloudFormation pre-defined template for creating VPC with public and private subnets

This pre-defined template creates a Virtual Private Cloud (VPC) on AWS with public and private subnets and sets up an Internet gateway, route table, and security groups within the VPC.

## Resources
- **VPC:** Creates a Virtual Private Cloud (VPC) with the CIDR block.
- **Internet Gateway:** Creates an Internet Gateway to allow communication between VPC and internet and attaches it to the VPC.
- **Public Subnet:** Creates a public subnet within the VPC with the CIDR block.
- **Private Subnets:** Creates two private subnets within the VPC with CIDR blocks.
- **Route Table:** Creates a route table to allow control of traffic within the VPC and associates it with the public subnet.
- **Security Groups:**: Creates security groups for web servers, HTTPS traffic, and database access.
