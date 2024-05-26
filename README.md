# tf-aws

This project creates an EKS cluster .

The main.tf does the following steps

1. Create a vpc, public and private subnets
2. Create EKS cluster wihin the VPC.
3. Add the CSI driver add-on for  interfacing with AWS storage
4. Added cloudwatch logging for Control plane logs

How to run

1. terraform init
2. terraform apply