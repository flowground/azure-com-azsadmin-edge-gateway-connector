# ![LOGO](logo.png) FabricAdminClient **flow**ground Connector

## Description

A generated **flow**ground connector for the FabricAdminClient API (version 2016-05-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-EdgeGateway/2016-05-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:35+03:00

## API Description

Edge gateway operation endpoints and objects.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns the list of all edge gateways at a certain location.

*Tags:* `EdgeGateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `api-version` - _required_ - Client API Version.
* `$filter` - _optional_ - OData filter parameter.

### Returns the requested edge gateway.

*Tags:* `EdgeGateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - Name of the resource group.
* `location` - _required_ - Location of the resource.
* `edgeGateway` - _required_ - Name of the edge gateway.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-edge-gateway-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
