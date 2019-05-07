# ![LOGO](logo.png) DataLakeStoreAccountManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataLakeStoreAccountManagementClient API (version 2016-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/datalake-store-account/2016-11-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:59+03:00

## API Description

Creates an Azure Data Lake Store account management client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Data Lake Store REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Store accounts within the subscription. The response includes a link to the next page of results, if any.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Gets subscription-level properties and limits for Data Lake Store specified by resource location.

*Tags:* `Locations`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - The resource location without whitespace.
* `api-version` - _required_ - Client Api Version.

### Checks whether the specified account name is available or taken.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - The resource location without whitespace.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Store accounts within a specific resource group. The response includes a link to the next page of results, if any.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - A Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified Data Lake Store account.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Store account.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Updates the specified Data Lake Store account information.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Creates the specified Data Lake Store account.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Attempts to enable a user managed Key Vault for encryption of the specified Data Lake Store account.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Store firewall rules within the specified Data Lake Store account.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified firewall rule from the specified Data Lake Store account.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `firewallRuleName` - _required_ - The name of the firewall rule to delete.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Store firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `firewallRuleName` - _required_ - The name of the firewall rule to retrieve.
* `api-version` - _required_ - Client Api Version.

### Updates the specified firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `firewallRuleName` - _required_ - The name of the firewall rule to update.
* `api-version` - _required_ - Client Api Version.

### Creates or updates the specified firewall rule. During update, the firewall rule with the specified name will be replaced with this new firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `firewallRuleName` - _required_ - The name of the firewall rule to create or update.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Store trusted identity providers within the specified Data Lake Store account.

*Tags:* `TrustedIdProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified trusted identity provider from the specified Data Lake Store account

*Tags:* `TrustedIdProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `trustedIdProviderName` - _required_ - The name of the trusted identity provider to delete.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Store trusted identity provider.

*Tags:* `TrustedIdProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `trustedIdProviderName` - _required_ - The name of the trusted identity provider to retrieve.
* `api-version` - _required_ - Client Api Version.

### Updates the specified trusted identity provider.

*Tags:* `TrustedIdProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `trustedIdProviderName` - _required_ - The name of the trusted identity provider. This is used for differentiation of providers in the account.
* `api-version` - _required_ - Client Api Version.

### Creates or updates the specified trusted identity provider. During update, the trusted identity provider with the specified name will be replaced with this new provider

*Tags:* `TrustedIdProviders`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `trustedIdProviderName` - _required_ - The name of the trusted identity provider. This is used for differentiation of providers in the account.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Store virtual network rules within the specified Data Lake Store account.

*Tags:* `VirtualNetworkRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified virtual network rule from the specified Data Lake Store account.

*Tags:* `VirtualNetworkRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `virtualNetworkRuleName` - _required_ - The name of the virtual network rule to delete.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Store virtual network rule.

*Tags:* `VirtualNetworkRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `virtualNetworkRuleName` - _required_ - The name of the virtual network rule to retrieve.
* `api-version` - _required_ - Client Api Version.

### Updates the specified virtual network rule.

*Tags:* `VirtualNetworkRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `virtualNetworkRuleName` - _required_ - The name of the virtual network rule to update.
* `api-version` - _required_ - Client Api Version.

### Creates or updates the specified virtual network rule. During update, the virtual network rule with the specified name will be replaced with this new virtual network rule.

*Tags:* `VirtualNetworkRules`

#### Input Parameters
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Store account.
* `virtualNetworkRuleName` - _required_ - The name of the virtual network rule to create or update.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-datalake-store-account-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
