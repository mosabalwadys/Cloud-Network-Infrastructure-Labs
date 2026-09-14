# AWS VPC Web Server Project

## Project Overview

This project demonstrates how to deploy a web server inside an AWS VPC using an EC2 instance in a public subnet.

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Internet Gateway
- Route Table
- Public Subnet
- Security Group
- Apache Web Server

## Network Configuration

- VPC CIDR: `10.0.0.0/16`
- Public Subnet CIDR: `10.0.1.0/24`
- EC2 Private IP: `10.0.1.236`
- EC2 Public IP: `44.197.133.210`
- Availability Region: `us-east-1`

## Apache Web Server Installation

The Apache web server was installed using the following commands:

```bash
sudo dnf update -y
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
