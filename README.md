# GetBearerToken

Azure REST Api で利用する Bearer Token を取得する LogicFlow<br />
Obtain Bearer Token to be used with Azure REST Api, with LogicApps！

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fahf0124%2FGetBearerToken%2Fmaster%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


POST で呼び出す際の JSON Schema.<br />
JSON schema for calling with POST.

{
  "properties": {
    "client_id": {
      "type": "string"
    },
    "client_secret": {
      "type": "string"
    },
    "resourceurl": {
      "type": "string"
    },
    "tenanntid": {
      "type": "string"
    }
  },
  "type": "object"
}

