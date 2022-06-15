# Configure AWS-CLI

Install aws-cli first and then be sure that you run 'aws configure' and that you configured aws-cli to be able to connect your aws account

https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html



### Provision an EKS cluster

```
# Provision EKS cluster at aws
terraform init && terraform plan -out 'tfplan' && terraform apply 'tfplan' --auto-approve
```