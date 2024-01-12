# VPC-Setup
Setting up the VPC for my Production using Terragrunt through a Jenkins Pipeline.

So this repo has 3 branches.
1: Main Branch: This code is with terragrunt configuring the resources through a CI-Cd Pipeline.
2: Terraform-Module: This branch is creating VPC using VPC module.
3: Simple-Terraform: This branch is creating VPC simply, using different terraform files for different resource.

NOTE: When creating a VPC we need to assign it a CIDR block. If we plan to peer multiple VPCs, we need to have unique CIDR ranges beforehand.
