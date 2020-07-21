---
title: Azure Monitor Logs reference - SecurityAlert
description: Reference for SecurityAlert table in Azure Monitor Logs.
ms.topic: reference
ms.service: azure-monitor
ms.subservice: logs
ms.author: bwren
author: bwren
ms.date: 7/2/2020
---

# SecurityAlert

 Alerts that been generated by security products.

## Categories

- Security
## Solutions

- AzureSecurityOfThings
- Security and Audit
- SecurityCenter
- SecurityCenterFree
- SecurityInsights




## Columns

|Column|Type|Description|
|---|---|---|
|AlertLink|string||
|AlertName|string||
|AlertSeverity|string||
|ConfidenceLevel|string||
|ConfidenceScore|real||
|Description|string||
|DisplayName|string||
|EndTime|datetime||
|Entities|string||
|ExtendedLinks|string||
|ExtendedProperties|string||
|IsIncident|bool||
|ProcessingEndTime|datetime||
|ProductComponentName|string||
|ProductName|string||
|ProviderName|string||
|RemediationSteps|string||
|ResourceId|string||
|SourceComputerId|string||
|StartTime|datetime||
|SystemAlertId|string||
|TimeGenerated|datetime||
|Type|string|The name of the table|
|VendorName|string||
|VendorOriginalId|string||
|WorkspaceResourceGroup|string||
|WorkspaceSubscriptionId|string||