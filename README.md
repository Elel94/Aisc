# Lab Terraform avancé sans provider
## Objectif
Mettre en place une pipeline CI/CD professionnelle autour d'un projet Terraform sans provider.
## Commandes locales
terraform fmt -recursive
terraform init
terraform validate
terraform plan -var-file=dev.tfvars
terraform plan -var-file=staging.tfvars
terraform plan -var-file=prod.tfvars
terraform apply -var-file=dev.tfvars
terraform output