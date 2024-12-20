1.Retrieve the resource group name from the lab.
az group list --query [].name
3.Create a new folder to hold your AKS configuration:
mkdir aks_cluster
cd aks_cluster
3.update the resorce group in terraform.tfvars
Update the RESOURCE_GROUP_NAME placeholder with the correct value.
4.deploy the terraform
terraform init
terraform apply
