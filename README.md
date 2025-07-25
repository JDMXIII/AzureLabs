The correct syntax for running the script to deploy the VM's in the lab

New-AzResourceGroupDeployment `
  -ResourceGroupName $RGName `
  -TemplateUri "https://raw.githubusercontent.com/JDMXIII/AzureLabs/main/azuredeploy.json" `
  -Verbose
