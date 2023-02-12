# Terraform-Project
About Terraform 
Terraform is an open-source infrastructure-as-code software tool created by HashiCorp.
Users define and provide data center infrastructure using a declarative configuration language known as HashiCorp Configuration Language, or optionally JSON.

Created a <b>VPC(Virtual Private Cloud)</b> with the help of terraform.
1. Created a vpc
2. Created aInternet Gateway
3. Created a custom route table
4. Created a subnet
5. Associated subnet with route table
6. Created Security group to allow port 22,80,443
7. Created a network interface with an ip in the subnet that was created in step 4
8. Assigned an elastic IP to the network interface created in step 7
9. Created Ubuntu server and install/enable apache2
