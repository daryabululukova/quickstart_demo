---
description: This template allows you to deploy a simple Windows VM using a few different options for the Windows version, using the latest patched version. This will deploy an A2 size VM in the resource group location and return the FQDN of the VM.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: vm-simple-windows
languages:
- bicep
- json
---
# Deploy a simple Windows VM


This template allows you to deploy a simple Windows [Generation 2 VM](https://docs.microsoft.com/azure/virtual-machines/generation-2) using a few different options for the Windows version, using the latest patched version. This will deploy a D2s_v3 size VM in the resource group location and return the fully qualified domain name of the VM.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdaryabululukova%2Fquickstart_demo%2Fmaster%2FVM%2Fazuredeploy.json)


If you're new to Azure virtual machines, see:

- [Azure Virtual Machines](https://azure.microsoft.com/services/virtual-machines/)
- [Azure Linux Virtual Machines documentation](https://docs.microsoft.com/azure/virtual-machines/linux/)
- [Azure Windows Virtual Machines documentation](https://docs.microsoft.com/azure/virtual-machines/windows/)
- [Template reference](https://docs.microsoft.com/azure/templates/microsoft.compute/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/?resourceType=Microsoft.Compute&pageNumber=1&sort=Popular)

If you're new to template deployment, see:

- [Azure Resource Manager documentation](https://docs.microsoft.com/azure/azure-resource-manager/)
- [Quickstart: Create a Windows virtual machine using an ARM template](https://docs.microsoft.com/azure/virtual-machines/windows/quick-create-template)

`Tags: Microsoft.Storage/storageAccounts, Microsoft.Network/publicIPAddresses, Microsoft.Network/networkSecurityGroups, Microsoft.Network/virtualNetworks, Microsoft.Network/networkInterfaces, Microsoft.Compute/virtualMachines`