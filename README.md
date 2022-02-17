# wordpress-azure-terraform

Use Terraform to provision an Azure virtual machine scale set running Wordpress.

## Prerequisites

* [Terraform](https://www.terraform.io)
* [Azure subscription](https://azure.microsoft.com/en-us/free)
* [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

## How to use

With Terraform and Azure CLI properly configured, you can run:

### `terraform init`

Prepare your working directory.

### `terraform plan`

Generate an execution plan.

### `terraform apply`

Apply changes to Azure cloud.


### test

```
resource "azurerm_lb" "lb" {
#   name                = "lb"
#   location            = azurerm_resource_group.rg.location
#   resource_group_name = azurerm_resource_group.rg.name
 
```