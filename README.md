# infrastructure

Assignment - 2

Create & Setup GitHub Repository for AWS Infrastructure

1. Create (Links to an external site.) a new private GitHub repository in the GitHub organization you created.
2. GitHub repository name must be infrastructure.
3. Grant TAs access to your GitHub repository.
4. Update README.md in your repository with instructions for setting up your infrastructure using Terraform.
5. Fork the GitHub repository in your namespace. You will do all development work on your fork.
6. All Terraform files should be in this repository.
7. Add appropriate .gitignore to your repository. A collection of useful .gitignore templates can be found here (Links to an external site.).

AWS Networking Setup

Here is what you need to do for networking infrastructure setup:

1. Create Virtual Private Cloud (VPC) (Links to an external site.).
2. Create subnets (Links to an external site.) in your VPC. You must create 3 subnets, each in a different availability zone in the same region in the same VPC.
3. Create an Internet Gateway (Links to an external site.) resource and attach the Internet Gateway to the VPC.
4. Create a public route table (Links to an external site.). Attach all subnets created above to the route table.
5. Create a public route in the public route table created above with destination CIDR block 0.0.0.0/0 and internet gateway created above as the target.

Infrastructure as Code with Terraform

For this objective, you must complete the following tasks:

1. Install and set up AWS command line interface.
2. Create a Terraform configuration file that will set up all the networking resources.
3. Values should not be hardcoded in your Terraform configuration files.
4. You must be able to use the same terraform configuration files in the same AWS account and region to create multiple VPCs including all of its resources (listed in the “AWS Networking Setup” section) such as subnets, internet gateway, route table, etc.

Instructions to Run 

1. terraform fmt
2. terraform plan
3. terraform apply
4. terraform destroy

Details
Name - Dwaraganath Setti Ashok
NUID - 001007680
Email - settiashok.d@northeastern.edu
