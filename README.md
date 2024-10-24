﻿# DeployInfraAWS
AWS VPC Setup with Terraform
This repository contains a Terraform configuration to set up a Virtual Private Cloud (VPC) in AWS. The configuration includes the creation of public and private subnets, route tables, an internet gateway, and a NAT gateway.

Table of Contents
Prerequisites
Usage
Variables
Resources
Tags
License
Prerequisites
Before using this configuration, ensure you have the following:

An AWS account.
Terraform installed on your local machine.
AWS CLI configured with appropriate credentials.
Usage
Clone this repository to your local machine:

git clone https://github.com/yourusername/your-repo.git
cd your-repo
Navigate to the directory containing the Terraform files.

Initialize the Terraform configuration:

terraform init
Review the planned changes:


terraform plan
Apply the changes to create the infrastructure:

terraform apply
Confirm the apply action when prompted.

To destroy the infrastructure, run:
terraform destroy
