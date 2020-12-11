# azure-node-sample-app
> az group create --name myResourceGroup --location westus
> az appservice plan create --name myPlan --resource-group myResourceGroup --sku F1
> az webapp list-runtimes
> az webapp create --name mydecazureserviceapp --resource-group myResourceGroup --plan myPlan --runtime "node|10.14"
> mydecazureserviceapp.azurewebsites.net
> az webapp browse --name mydecazureserviceapp --resource-group myResourceGroup
> az webapp deployment user set --user-name "mydecazureserviceapp" --password "mydecazureserviceapp@123"
> az webapp deployment source config-local-git --name mydecazureserviceapp --resource-group myResourceGroup
> https://mydecazureserviceapp@mydecazureserviceapp.scm.azurewebsites.net/mydecazureserviceapp.git
> git remote add azure https://mydecazureserviceapp@mydecazureserviceapp.scm.azurewebsites.net/mydecazureserviceapp.git
> git push azure main