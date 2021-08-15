# 1st_arm_template

```
az group create --name arm-vscode --location eastus
```

```
az deployment group create --resource-group arm-vscode --template-file azuredeploy.json --parameters azuredeploy.parameters.json
```

```
az group delete --name arm-vscode
```