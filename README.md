# Azure_RestAPi_GetUsersy
Extracting Azure API Manager Users can be a pain  when operatining with thousands of users.
APIM provided Rest APis with page restrictions of 1000 users per call.

using python pandas and request liberiries, able to extract Firstname, Lastname, Email and state and saving them in a local CSV file 

In order to use the code, below  will be assumed already 

Using  the Azure CLI to get   a Token 
Command:  az account get-access-token
Token = (Copy the Token in the variable )

Run Command "az resource list" on Azure CLI and get the values for the below 
subscriptionId = "subscriptionId"
resourceGroupName = "resourceGroupName"
serviceName = "serviceName"


if this was helpfull, Please share  and am open to improments 
