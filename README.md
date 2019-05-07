# ![LOGO](logo.png)  API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the  API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-ResourceProvider/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets publishing user

#### Input Parameters
* `api-version` - _required_ - API Version

### Updates publishing user

#### Input Parameters
* `api-version` - _required_ - API Version

### Gets the source controls available for Azure websites.

#### Input Parameters
* `api-version` - _required_ - API Version

### Gets source control token

#### Input Parameters
* `sourceControlType` - _required_ - Type of source control
* `api-version` - _required_ - API Version

### Updates source control token

#### Input Parameters
* `sourceControlType` - _required_ - Type of source control
* `api-version` - _required_ - API Version

### Gets a list of meters for a given location.

#### Input Parameters
* `billingLocation` - _optional_ - Azure Location of billable resource
* `osType` - _optional_ - App Service OS type meters used for
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Check if a resource name is available.

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Gets list of available geo regions plus ministamps

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Get a list of available geographical regions.

#### Input Parameters
* `sku` - _optional_ - Name of SKU used to filter the regions.
    Possible values: Free, Shared, Basic, Standard, Premium, Dynamic, Isolated, PremiumV2, ElasticPremium, ElasticIsolated.
* `linuxWorkersEnabled` - _optional_ - Specify <code>true</code> if you want to filter to only regions that support Linux workers.
* `xenonWorkersEnabled` - _optional_ - Specify <code>true</code> if you want to filter to only regions that support Xenon workers.
* `linuxDynamicWorkersEnabled` - _optional_ - Specify <code>true</code> if you want to filter to only regions that support Linux Consumption Workers.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all apps that are assigned to a hostname.

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all premier add-on offers.

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### List all SKUs.

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.

#### Input Parameters
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Move resources between resource groups.

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Validate if a resource can be created.

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Validate if the container settings are correct.

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

### Validate whether a resource can be moved.

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the resource group to which the resource belongs.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-resource-provider-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
