---
title: "CloudPcSharedUseServicePlan resource type"
description: "Represents a Cloud PC shared use servicePlan."
author: "AshleyYangSZ"
ms.localizationpriority: medium
ms.prod: "cloud-pc"
doc_type: resourcePageType
---

# cloudPcSharedUseServicePlan resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents a Cloud PC shared use servicePlan.

## Methods

| Method                                                                                  | Return type                                                                       | Description                                                                                                               |
| :-------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------ |
| [List provisioningPolicies](../api/virtualendpoint-list-provisioningpolicies.md)        | [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) collection | List properties and relationships of the [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) objects.  |
| [Get cloudPcProvisioningPolicy](../api/cloudpcprovisioningpolicy-get.md)                | [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md)            | Read the properties and relationships of a [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) object. |
| [Create cloudPcProvisioningPolicy](../api/virtualendpoint-post-provisioningpolicies.md) | [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md)            | Create a new [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) object.                               |
| [Update cloudPcProvisioningPolicy](../api/cloudpcprovisioningpolicy-update.md)          | [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md)            | Update the properties of a [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) object.                 |
| [Delete cloudPcProvisioningPolicy](../api/cloudpcprovisioningpolicy-delete.md)          | None                                                                              | Delete a [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) object.                                   |
| [Assign cloudPcProvisioningPolicy](../api/cloudpcprovisioningpolicy-assign.md)          | None                                                                              | Assign a [cloudPcProvisioningPolicy](../resources/cloudpcprovisioningpolicy.md) to user groups.                           |

## Properties

| Property      | Type         | Description                                                            | Key | Required | ReadOnly |
| ------------- | ------------ | ---------------------------------------------------------------------- | --- | -------- | -------- |
| `id`          | `Edm.String` | The unique ID of shared-use service plan.                              | Yes | Yes      | Yes      |
| `displayName` | `Edm.String` | The display name of shared-use service plan.                           | No  | Yes      | Yes      |
| `usedCount`   | `Edm.Int32`  | Indicates the number of service plans that are in use for the account. | No  | Yes      | Yes      |
| `totalCount`  | `Edm.Int32`  | Total number of shared-use service plans purchased by customer.        | No  | Yes      | Yes      |

## JSON representation

The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.cloudPcSharedUseServicePlan",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->

``` json
{
  "@odata.type": "#microsoft.graph.cloudPcSharedUseServicePlan",
  "id": "String (identifier)",
  "displayName": "String",
  "usedCount": "Int32",
  "totalCount": "Int32"
}
```
