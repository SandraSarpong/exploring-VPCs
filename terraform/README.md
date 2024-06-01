This script generated with PULUMI creates the following:

- A VPC with public and private subnets across two availability zones.
- An Internet Gateway for the public subnets.
- Route tables for public subnets.
- Security groups to allow SSH and internal communication.
- EC2 instances in both public and private subnets.

NB: You can SSH into a public instance using one of the public IPs from the output and ping the private instance using its private IP.
