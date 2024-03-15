# Important Commands 

## Development

> Start the flask app in development mode to auto reload

```bash
FLASK_ENV=development flask run
```
----
## Deployment 
> Deploy the webapp on Azure 
```
az login && 
az webapp up --runtime PYTHON:3.9 --sku B1 --logs
```

----
## Updating the app based on the changes pushed to main 
> Make sure to change the `Deployment Center` and use `Github` configuration. This will take care of 
> updating the app on changes pushed to main.

----

## Custom DNS name 


Step by step guide available at 👉 [AzureDNSHostingGuide](https://learn.microsoft.com/en-gb/azure/app-service/app-service-web-tutorial-custom-domain?WT.mc_id=AZ-MVP-5003203&tabs=root%2Cazurecli)


----

For further help please refer to 👉 [AzureGuide](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cvscode-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli). 