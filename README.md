# terraform-proxmox-template
Terraform Build Template Code For Proxmox

Terraform Plan & Terraform Apply - See Planned output of resources to deploy and apply to deploy the planned resources
```
terraform plan -var-file="credentials.tfvars" 
```
```
terraform apply -var-file="credentials.tfvars" 
```

Terraform Destroy - Destroy resources
```
terraform destroy -var-file="credentials.tfvars" 
```