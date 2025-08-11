### Useful commands:

- `terraform init`

  Initializes the Terraform working directory (`.terraform`).

- `terraform plan -out=plan.tfplan`

  Creates an execution plan, showing what actions Terraform will take.

- `terraform apply "plan.tfplan"`

  Applies the changes required to reach the desired state of the configuration.

- `terraform destroy` or `terraform plan -destroy=destroy.tfplan` and then `terraform apply "destroy.tfplan"`

  Destroys the Terraform-managed infrastructure.