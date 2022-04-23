# CloudFormation Template
CloudFormation template for highly available & secure WordPress deployment with RDS and custom VPC on AWS.
## Networking Layer
This CloudFormation template creates a custom VPC with 2 public and 2 private subnets.
### Components
- VPC
- 4 Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
## Security Layer
This CloudFormation template creates security groups.
### Components
- Load Balancer Security Group
- Database Security Group
- Application Security Group
## Data Layer
This CloudFormation template creates a RDS with MySQL Engine.
### Components
- Subnet Group
- RDS
## Compute Layer
This CloudFormation template creates a ASG and LB to deploy the application.
### Components
- Launch Configuration
- Auto Scaling Group
- Scaling Policy
- Target Group
- Load Balancer
- HTTP Listener
- HTTPS listener

