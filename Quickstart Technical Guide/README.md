# AWS Qickstart Templates

Cloudticity is providing these Quickstart templates to provision pre-configured resources in your AWS account including: a baseline development VPC, A Microsoft Windows server with IIS installed, or single instance LAMP stack.  

Each Quick start is easily deployed by clicking the link provided. Some notes regarding the templates and the deployment process:
  * You must be signed in to an existing AWS account.
  * Your user account must have enough privileges to run Cloudformation templates and create resources, including IAM roles.
  * A new window will open to create the resources using Cloudformation.
  * Check the box next to "I acknowledge that AWS CloudFormation might create IAM resources with custom names."
  * The templates provided will create resources in your AWS account. All attempts have been made to use free-tier instance types, but charges may be incurred depending on other resources used.
  * **The templates provided are intended for for non-production use only**.  They have been simplified for the purpose of this event and should only be used for development and testing.

  The Templates

   * Single AZ VPC with a public and private subnet.  This quickstart can be used to create your development VPC.
     * [Run the VPC Quickstart](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://s3.amazonaws.com/cloudticity-connectathon-public/create_new_vpc.yaml)
  * Windows 2019 Server with IIS. You can run this quickstart after creating your development VPC, or install the instance  in an existing VPC 
     * [Run the Windows IIS Quickstart](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://s3.amazonaws.com/cloudticity-connectathon-public/create_windows_in_existing_vpc.yaml)
 * Creates a LAMP stack on a single Amazon EC2 instance with a local MySQL database for storage.  You can run this quickstart after creating your development VPC, or install the instance  in an existing VPC 
     * [Run the LAMP Quickstart](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://s3.amazonaws.com/cloudticity-connectathon-public/create_linux_in_existing_vpc.yaml)

