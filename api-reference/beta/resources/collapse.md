---
title: "collapse resource type"
description: "Indicates the specification to collapse search results"
ms.localizationpriority: medium
author: "cxiang"
ms.prod: "search"
doc_type: "resourcePageType"
---

# collapse resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Indicates the specification to collapse search results.

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|collapse|[collapseOption](collapseOption.md) collection|Specifies the a set of criteria to collapse results. Optional.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.collapse",
  "baseType": null
}-->

```json
{
  "collapse": [{"@odata.type": "microsoft.graph.collapseOption"}]
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "collapse resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->