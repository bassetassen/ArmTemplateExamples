# ArmTemplateExamples

Always validate template with Azure CLI.

```
az group deployment validate --template-file template.json --parameters parameters.json --resource-group <resource group name>
```

For deployment with Azure CLI.
```
az group deployment create --template-file template.json --parameters parameters.json --resource-group <resource group name>
```