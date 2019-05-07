# ![LOGO](logo.png) Security Insights **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Insights API (version 2019-01-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/securityinsights-SecurityInsights/2019-01-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:56+03:00

## API Description

API spec for Microsoft.SecurityInsights (Azure Security Insights) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all operations available Azure Security Insights Resource Provider.

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.

### Gets all alert rules.

*Tags:* `Alert Rules`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Delete the alert rule.

*Tags:* `Alert Rules`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID

### Gets the alert rule.

*Tags:* `Alert Rules`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID

### Creates or updates the alert rule.

*Tags:* `Alert Rules`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID

### Gets all actions of alert rule.

*Tags:* `Actions`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID

### Delete the action of alert rule.

*Tags:* `Actions`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID
* `actionId` - _required_ - Action ID

### Gets the action of alert rule.

*Tags:* `Actions`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID
* `actionId` - _required_ - Action ID

### Creates or updates the action of alert rule.

*Tags:* `Actions`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `ruleId` - _required_ - Alert rule ID
* `actionId` - _required_ - Action ID

### Gets all bookmarks.

*Tags:* `Bookmarks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Delete the bookmark.

*Tags:* `Bookmarks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `bookmarkId` - _required_ - Bookmark ID

### Gets a bookmark.

*Tags:* `Bookmarks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `bookmarkId` - _required_ - Bookmark ID

### Creates or updates the bookmark.

*Tags:* `Bookmarks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `bookmarkId` - _required_ - Bookmark ID

### Gets all cases.

*Tags:* `Cases`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Delete the case.

*Tags:* `Cases`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `caseId` - _required_ - Case ID

### Gets a case.

*Tags:* `Cases`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `caseId` - _required_ - Case ID

### Creates or updates the case.

*Tags:* `Cases`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `caseId` - _required_ - Case ID

### Gets all data connectors.

*Tags:* `Data Connectors`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Delete the data connector.

*Tags:* `Data Connectors`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `dataConnectorId` - _required_ - Connector ID

### Gets a data connector.

*Tags:* `Data Connectors`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `dataConnectorId` - _required_ - Connector ID

### Creates or updates the data connector.

*Tags:* `Data Connectors`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `dataConnectorId` - _required_ - Connector ID

### Gets all entities.

*Tags:* `Entities`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Gets an entity.

*Tags:* `Entities`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `entityId` - _required_ - entity ID

### Gets all office365 consents.

*Tags:* `Office Consents`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.

### Delete the office365 consent.

*Tags:* `Office Consents`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `consentId` - _required_ - consent ID

### Gets an office365 consent.

*Tags:* `Office Consents`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `consentId` - _required_ - consent ID

### Gets a setting.

*Tags:* `Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `settingsName` - _required_ - The setting name. Supports- Fusion, UEBA

### Updates the setting.

*Tags:* `Settings`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
    Possible values: 2019-01-01-preview.
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `operationalInsightsResourceProvider` - _required_ - The namespace of workspaces resource provider- Microsoft.OperationalInsights.
* `workspaceName` - _required_ - The name of the workspace.
* `settingsName` - _required_ - The setting name. Supports- Fusion, UEBA

## License

**flow**ground :- Telekom iPaaS / azure-com-securityinsights-security-insights-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
