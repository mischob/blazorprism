# Pai - Customer Relationship Management System


## Implementation Details

### SIP Phone integration

Using Yealink T48S to send Events to an Service Bus administered by a small web app :

Off Hook : 
https://paisip.azurewebsites.net/api/sip/token/mysecret/offhook/1234/model/mike

On Hook :
http://paisip.azurewebsites.net/api/sip/token/mysecret/onhook/$ip/model/$model

Outgoing Call :
http://paisip.azurewebsites.net/api/sip/token/mysecret/outgooing/$ip/call/$calledNumber

Sample for using on local machiene for Off Hook : 
http://192.168.0.101:5001/api/sip/token/mysecret/offhook/$ip/model/$model

## Versioning

We use [SemVer](http://semver.org/) for versioning. 


## Authors

* **Mike Schober** - *Initial work* - 


## License

Only for use within Daimler AG.

## Acknowledgments


## Intrestings Links 

[Blazor Authorization](https://gist.github.com/SteveSandersonMS/175a08dcdccb384a52ba760122cd2eda)
[Blazor Elements] (https://blazor.radzen.com/get-started)
[SignalR in Blazor] (https://github.com/conficient/BlazorChatSample)
