## How to use this repository 
This is a basic example repository that demonstrates the process of deploying AWS Amplify app using reactjs with Terraform.

### Prerequisite 
1. Have a Basic understanding of Terraform 
2. Have Terraform and AWS CLI installed on your workstation 
3. Establish a means of authenticating your AWS CLI with AWS. This means that you can access AWS Services from your termainal.

### Steps 
1. Add your `s3 bucket and dynamoDB details` if you intend to keep the states. 
2. Run the commands in this order; `Terraform init` && `Terraform plan -var-file=values.tfvars` && `Terraform apply -var-file=values.tfvars` && `Terraform destroy -var-file=values.tfvars`
3. `terraform destroy` command will destroy the infrastructure created with this terraform configuration.