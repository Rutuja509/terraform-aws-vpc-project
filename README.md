# Terraform AWS VPC Project

## Overview
This project creates AWS infrastructure using Terraform.


## Resources Created

- 1 VPC (10.0.0.0/16)
- 1 Public Subnet (10.0.1.0/24)
- 1 Internet Gateway
- 1 Route Table
- 1 Security Group
- 1 EC2 Instance (t3.micro)


## Output

- Instance ID: i-0d107c03e51c56850  
- Public IP: 52.66.215.76  
- VPC ID: vpc-0765d3d4d15df2d16  


## Terraform Commands Used

- terraform init  
- terraform plan  
- terraform apply  


## Architecture Flow

VPC → Subnet → Internet Gateway → Route Table → Security Group → EC2



## AWS Console Output

![EC2 Instance Created](Screenshot/ec2-instance-created.png)

![EC2 Instance Details](Screenshot/ec2-instance-details.png)