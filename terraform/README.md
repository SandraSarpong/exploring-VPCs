This script creates:

A VPC with public and private subnets across two availability zones.
An Internet Gateway for the public subnets.
Route tables for public subnets.
Security groups to allow SSH and internal communication.
EC2 instances in both public and private subnets.
You can SSH into a public instance using one of the public IPs from the output, and then ping the private instance using its private IP.
