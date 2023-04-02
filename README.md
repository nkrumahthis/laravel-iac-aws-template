# laravel iac template

A template for server provisioning and continuous deployment.
This this CD set up will:

1. run all tests
2. provision a free-tier eligible server on AWS with docker installed
3. run your application

## Usage

run `terraform -chdir=terraform init` and replace the .terraform.lock.hcl file with yours.
just push/merge to main.
