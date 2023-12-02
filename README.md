# Terraform-EC2

Infrastructure Overview

This Terraform script orchestrates a basic web server infrastructure on AWS. It sets up a Virtual Private Cloud (VPC) with an internet gateway, a subnet, security groups, and an EC2 instance running Ubuntu with Apache2.

Key Components:
VPC: Isolated network environment (10.0.0.0/16 CIDR) within AWS.
Internet Gateway: Provides internet access to the VPC.
Subnet: Defines a network (10.0.1.0/24) within the VPC in us-east-1a.
Security Group: Controls inbound/outbound traffic (SSH, HTTP, HTTPS).
Elastic IP: Public IP attached to the EC2 instance.
EC2 Instance: Ubuntu server running Apache2, serving content at /var/www/html/index.html.
Purpose:
This infrastructure offers a foundational setup for hosting a web application or website. It enables easy deployment and management of a basic web server environment on AWS using Terraform.
