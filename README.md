# Deadline Cloud Customer Managed Fleet Deploy

Easily stand up a Deadline Cloud customer managed fleet (CMF) in your VPC.

## Prerequisits

- Deadline Cloud render farm deployed in your AWS account
- VPC with private subnets and nat gateway for internet access

## What This Deploys

Option to have blender auto install on base image. Useful for testing if the fleet is working correctly.

This CloudFormation template deploys:

- EC2 AMI configured as Deadline Worker node
- Required IAM roles and policies for worker nodes
- Security groups for Deadline Cloud communication
- Optional Blender installation on the base image for testing purposes

The deployment includes automatic registration of worker nodes with your existing Deadline Cloud render farm.


## How To Deploy



## Clean up


## Security Considerations
Worker nodes should ideally be deployed in private subnets

Security groups are configured to allow only necessary communication

IAM roles follow the principle of least privilege
