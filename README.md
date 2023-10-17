# A Terraform codebase for building on-demand AWS Dev environment.

Terraform project to create an on-demand dev environment with an AWS EC2 instance that can be spun up and down within seconds.

Deploy AWS resources and an EC2 instance that you can SSH into to have your own redeployable environment.

## What's in it?

⌨️ AWS IAM Setup
⌨️ Local Environment Setup
⌨️ Let's Build! (7:22)
⌨️ AWS Provider and Terraform Init
⌨️ A VPC and Terraform Apply
⌨️ The Terraform State
⌨️ Terraform Destroy
⌨️ A Subnet and Referencing
⌨️ An IGW and Terraform fmt
⌨️ A Route Table
⌨️ A Route Table Association
⌨️ A Security Group
⌨️ An AMI Datasource
⌨️ A Key Pair
⌨️ An EC2 Instance
⌨️ Userdata and the File Function
⌨️ SSH Config Scripts
⌨️ The Provisioner and Templatefile
⌨️ The Deployment and Replace
⌨️ Variables
⌨️ Variable Precedence
⌨️ Conditional Expressions
⌨️ Outputs

## Prerequisite
1. [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
2. [Github account](https://github.com/)
3. [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli)
4. [AWS account](https://aws.amazon.com/)
5. [AWS CLI installed](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and [configured] (https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)
6. [Docker](https://docs.docker.com/engine/install/) with at least 4GB of RAM and Docker Compose v1.27.0 or later

## Installation

Run these commands to set up your dev environment on the cloud.

```
git clone git@github.com:scriptstar/terraform-dev-env.git
```

This command will create an EC2 instance in your AWS account.

```
terraform apply
```

This command will destroy the above EC2 instance in your AWS account.

```
terraform destroy
```