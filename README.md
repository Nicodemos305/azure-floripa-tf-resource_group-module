# azure-floripa-tf-resource_group-module

# Terraform Azure Resource Group Module

Este módulo Terraform cria um Azure Resource Group.

## Requisitos

- Terraform 1.0 ou superior
- Credenciais para autenticação no Azure

## Variáveis

- **`name`** (string): Nome do Resource Group. **Obrigatório**
- **`location`** (string): Localização/região onde o Resource Group será criado. **Obrigatório**

## Outputs

- **`resource_group_name`**: Nome do Resource Group criado.
- **`resource_group_id`**: ID do Resource Group criado.

Consulte a [documentação do Terraform](https://www.terraform.io/docs) para mais detalhes sobre como utilizar módulos e configurar o provider Azure.
