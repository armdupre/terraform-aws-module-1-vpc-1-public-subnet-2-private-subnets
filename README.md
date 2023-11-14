# module-1-vpc-1-public-subnet-2-private-subnets/aws

## Description
Terraform module for Vpc deployment on Amazon Web Services

## Deployment
This module creates a topology with a single virtual private cloud having a single public facing subnet and two private subnets.

## Usage
```tf
module "Vpc" {
	source = "armdupre/module-1-vpc-1-public-subnet-2-private-subnets/aws"
	InboundIPv4CidrBlocks = [ "1.1.1.1/32" ]
}
```