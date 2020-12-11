# azure-node-sample-app
> az group create --name myResourceGroup --location westus
> az appservice plan create --name myPlan --resource-group myResourceGroup --sku F1
> az webapp list-runtimes
> az webapp create --name mydecazureserviceapp --resource-group myResourceGroup --plan myPlan --runtime "node|10.14"
> mydecazureserviceapp.azurewebsites.net
> az webapp browse --name mydecazureserviceapp --resource-group myResourceGroup
> az webapp deployment user set --user-name mydecazureserviceapp --password mydecazureserviceapp@123 --resource-group myResourceGroup