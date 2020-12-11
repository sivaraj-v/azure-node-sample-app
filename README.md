# azure-node-sample-app

```
> az group create --name myResourceGroup --location westus
> az appservice plan create --name myPlan --resource-group myResourceGroup --sku F1
> az webapp list-runtimes
> az webapp create --name mydecazureserviceapp --resource-group myResourceGroup --plan myPlan --runtime "node|10.14"
> mydecazureserviceapp.azurewebsites.net
> az webapp browse --name mydecazureserviceapp --resource-group myResourceGroup
> az webapp deployment user set --user-name "mydecazureserviceapp" --password "yourpassword"
> az webapp deployment source config-local-git --name mydecazureserviceapp --resource-group myResourceGroup
> https://mydecazureserviceapp@mydecazureserviceapp.scm.azurewebsites.net/mydecazureserviceapp.git
For Azure Origin
> git remote add azure https://mydecazureserviceapp@mydecazureserviceapp.scm.azurewebsites.net/mydecazureserviceapp.git
> git push azure master
For Github Origin
> git push origin master
> https://mydecazureserviceapp.scm.azurewebsites.net/
```

Ref: 
Using CLI:
https://docs.microsoft.com/en-us/azure/developer/javascript/tutorial-vscode-azure-cli-node-04
Using VScode:
https://docs.microsoft.com/en-gb/azure/app-service/quickstart-nodejs?pivots=platform-windows

https://github.com/sivaraj-v/azure-node-sample-app.git