# Cloud Café - AWS Application Load Balancer Project

## Overview

Cloud Café demonstrates how AWS Application Load Balancer distributes traffic across multiple EC2 instances.

## Architecture

Users
↓
Application Load Balancer
↓ ↓
EC2 Server 1 EC2 Server 2

## AWS Services Used

- EC2
- Application Load Balancer
- Target Group
- Security Groups
- VPC

## Features

- Traffic Distribution
- Health Checks
- High Availability
- Fault Tolerance

## Project Steps

1. Launch EC2 Instances
2. Install Nginx
3. Create Target Group
4. Create ALB
5. Register Targets
6. Configure Health Checks
7. Test Load Balancing

## Demo

Refresh ALB DNS URL multiple times to see requests routed between Server 1 and Server 2.