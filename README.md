# Cloudenv

CloudEnv is a set of infrastructure setup configration and scripts for public cloud providers.

## Prerequisites

1. [Terraform](https://www.terraform.io) installed.

## Usage

1. Initilize modules by `terraform init`.
2. Setup your cloud provider `access_id` and `access_key` in `credential.tfvars` which save your credentials. (It won't be committed as an ignore file in `.gitignore`).
3. Plan or Apply your infrastructure settings by `terraform plan` or `terraform apply` with `-var-file` with `credential.tfvars` and other `.tfvars` files.

## LICENSE

[LICENSE](/LICENSE)
