#Install

Install Bicep: https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/install

```
az deployment group create --resource-group bicep-learning-rg --template-file main.bicep --parameters parameters.json
```

```
az deployment group create --template-file main.bicep --parameters environmentName=Production location=westus3
```