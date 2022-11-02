

terraform init

terraform plan -out tfplan -var resource_group_name=VALUE -var location="France Central" -var resources_suffix="mfo-nfs-2022" -var sql_administrator_login=VALUE -var sql_administrator_password=VALUE

terraform apply tfplan -auto-approve
