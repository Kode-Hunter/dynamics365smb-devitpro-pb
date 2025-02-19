---
title: "AllowScheduling Property"
description: "Sets whether a report can be scheduled to run in the background."
ms.author: solsen
ms.custom: na
ms.date: 06/23/2021
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# AllowScheduling Property
> **Version**: _Available or changed with runtime version 6.2._

Sets whether a report can be scheduled to run in the background.

## Applies to
-   Report

[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Property Value  

**true** if a report can be scheduled; otherwise, **false**. The default is **true**.  

## Syntax

```AL
AllowScheduling = false;
```

## Remarks

When set to **false**, the report won't support multiple previews. **false** cancels the effect of the [SaveValues](devenv-savevalues-property.md) request page property, which enables the multiple previews feature.

## See Also  

[Report Properties](devenv-report-properties.md)  
[SaveValues Property](devenv-savevalues-property.md)  