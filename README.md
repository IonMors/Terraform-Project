# Terraform-Project
About Terraform 
Terraform is an open-source infrastructure-as-code software tool created by HashiCorp.
Users define and provide data center infrastructure using a declarative configuration language known as HashiCorp Configuration Language, or optionally JSON.

Created a VPC(Virtual Private Cloud) with the help of terraform.
1. Created vpc
2. Create Internet Gateway
3. Create custom route table
4. Create a subnet
5. Associate subnet with route table
6. Create Security group to allow port 22,80,443
7. Create a network interface with an ip in the subnet that was created in step 4
8. Assign an elastic IP to the network interface created in step 7
9. Create Ubuntu server and install/enable apache2
