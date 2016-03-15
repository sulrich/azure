# azure
This ARM template deploys a VM-Series next generation firewall VM in an Azure resource group. The VM will be configured with 3 interfaces that map to 3 subnets: Mgmt, Untrust and Trust. This template allows the user to select a new/existing resource group and storage account, and creates new VNET and subnets.  

This template uses the BYOL SKU for VM-Series. VM-Series image details for PAN-OS 7.1.0:
* Publisher Name: paloaltonetworks
* Offer name:
* SKU:
* Version: "latest"

<a href="https://azuredeploy.net/?repository=https://raw.githubusercontent.com/PaloAltoNetworks/azure/master/basic-template1-byol/CreateUiDefinition.json?token=AJHjA_JvAm6B2B4zGArVKJdUVv56oJQjks5W8bBpwA%3D%3D" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>