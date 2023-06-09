---
description: This template creates a Key Vault and a list of secrets within the key vault as passed along with the parameters
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: key-vault-secret-create
languages:
- json
- bicep
---
# Create a Key Vault and a list of secrets


This template creates a key vault with a multiple access policies, and a list of secrets. Instead of just using an array for the secret creation, this template wraps an array in a [secureObject](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-authoring-templates#parameters). Using a secureObject instead of an array type means that the values you pass, cannot be read back in the portal after the deployment.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdaryabululukova%2Fquickstart_demo%2Fmaster%2FKeyVault%2Fazuredeploy.json)


Resource iteration is used in this template. For more information, see

- [Create multiple instances](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-create-multiple)
- [Tutorial: create multiple instances](https://docs.microsoft.com/azure/azure-resource-manager/resource-manager-tutorial-create-multiple-instances)

If you are new to Azure Key Vault, see:

- [Azure Key Vault service](https://azure.microsoft.com/services/key-vault/)
- [Azure Key Vault documentation](https://docs.microsoft.com/azure/key-vault/)
- [Azure Key Vault template reference](https://docs.microsoft.com/azure/templates/microsoft.keyvault/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/?resourceType=Microsoft.Keyvault)

If you are new to the template development, see:

- [Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)
- [Use Azure Key Vault to pass secure parameter value during deployment](https://docs.microsoft.com/azure/azure-resource-manager/resource-manager-keyvault-parameter)
- [Tutorial: Integrate Azure Key Vault in Resource Manager Template deployment](https://docs.microsoft.com/azure/azure-resource-manager/resource-manager-tutorial-use-key-vault)

Tags: Azure Key Vault, Key Vault, Secrets, Resource Manager, Resource Manager templates, ARM templates

`Tags: Microsoft.KeyVault/vaults, Microsoft.KeyVault/vaults/secrets`