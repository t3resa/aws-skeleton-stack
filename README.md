*SKELETON STACK*

This is an AWS Cloudformation script that is used to download dependencies to your host.
 - Within my script you can see that I clone a repository, copy a .env file. then have sed commands to replace their text with my unique values.

This script spins up a VPC, Subnet, and Internet Gateway.

The user is prompted for inputs named under parameters.