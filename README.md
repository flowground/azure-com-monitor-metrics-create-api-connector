# ![LOGO](logo.png) Azure Metrics **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Metrics API (version 2018-09-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-metricsCreate_API/2018-09-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:38:28+03:00

## API Description

A client for issuing REST requests to the Azure metrics service.

## Authorization

This API does not require authorization.

## Actions

### **Post the metric values for a resource**.

*Tags:* `Metrics`

#### Input Parameters
* `Content-Type` - _required_ - Supports application/json and application/x-ndjson
* `Content-Length` - _required_ - Content length of the payload
* `Authorization` - _required_ - Authorization token issue for issued for audience "https:\\monitoring.azure.com\"
* `subscriptionId` - _required_ - The azure subscription id
* `resourceGroupName` - _required_ - The ARM resource group name
* `resourceProvider` - _required_ - The ARM resource provider name
* `resourceTypeName` - _required_ - The ARM resource type name
* `resourceName` - _required_ - The ARM resource name

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-metrics-create-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
