# Day 2

## To download the terraform providers, you can refer the below Terraform registry portal
<pre>
https://registry.terraform.io/providers/hashicorp/azurerm/latest  
</pre>

## Lab - Login to azure portal using az command line tool
```
az version
az login
```

Expected output
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/27bd1c9c-49ba-4a17-b838-3247d4895013)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/a3651a74-9173-4188-89dc-7376a46a7da7)

## Lab - Loing to azure portal using Terraform 
```
cd ~/terraform-july-2024
git pull
cd Day2/azure-login
cat azure-login.tf
terraform init
terraform apply --auto-approve
```

Expected ouptut
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/f6ad4203-b6fe-4c2d-be4e-f9755ef36b69)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/c57e0c62-fb45-4c1f-a56a-b5248b3adf41)

## Lab - Finding the images availble in a specific azure region
```
az vm image list --location eastus2
```

Expected output
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/39ee56ec-8226-4023-be6d-ff156df4b59b)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/86aa5f3e-2c96-4d32-b40d-6dbcabc87773)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/a183f8d7-7013-4acd-b020-5ce23c51bd59)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/a6cd6991-ee0f-4278-baa4-86d354c64ad5)
![image](https://github.com/tektutor/terraform-july-2024/assets/12674043/8df1cf3d-c511-4ad8-8021-8a65108ae33c)
