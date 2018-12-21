**ABOUT**

LAMP_AZ consists of a cloudformation templates to provision a LAMP stack (one EC2 with httpd & php installed, as well as a single-AZ RDS for MySQL).

**Instructions**

When you launch the cloudformation template, there are parameters you need to fill in.
*- DBAllocatedStorage: MySQL database size
*- DBInstanceClass: the database instance type of RDS
*- DBName: Name of database created in RDS
*- DBUser: username of mysql database access
*- DBPassword: Password for MySQL database access
*- InstanceType: web server instance type
*- KeyName: Name of an existing EC2 SSH Keypair
*- SSHLocation: the IP address range that can be used to SSH to the web server EC2 instance 
*- VPCid: ID of you existing VPC
*- Subnets: VPC subnet to deploy EC2 and RDS
