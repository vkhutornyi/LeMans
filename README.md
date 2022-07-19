# How to install ARM template

##Prerequisites
- You must have installed and configured Twilio SendGrid in your Azure Subscription to be able to receive email alerts from Logic Apps.
- You must have installed and configured an On-premises data gateway for your onpremise external system

# [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvkhutornyi%2FLeMans%2Fmain%2Fazuredeploy.json) MAIN solution

# [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvkhutornyi%2FLeMans%2Fmain%2FazuredeployEX.json) EX system connectors

# Post deployment tasks
- Find external system deployed web connector and fill out all requred fields
 ![Edit web connector API](./20220718210245.png)

- Make sure the status is changes to "connected"
![Check the status](./20220718210311.png)

- Find sendgrid deployed web connector and fill out the API Key field
 ![Edit web connector API](./20220719105654.png)

- Make sure the status is changes to "connected"
![Check the status](./20220719111425.png)