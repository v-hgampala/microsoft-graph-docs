---
title: "collapseOption resource type"
description: "Specifies the collapse criteria of search results."
ms.localizationpriority: medium
author: "cxiang"
ms.prod: "search"
doc_type: "resourcePageType"
---

# collapseOption resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Specifies the criteria used for collapsing search results. Applies only to sortable/refinable property.

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|fields|String Collection| Defines the collapse criteria to trim duplicates results. The properties in this collection must be sortable/refinable property. Required.|
|limit|Int16| Defines a max limit count for this fields. This numeric value must be a positive integer. Required.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.collapseOption",
  "baseType": null
}-->

```json
{
  "fields": ["String"],
  "limit": 1024
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "collapseOption resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->