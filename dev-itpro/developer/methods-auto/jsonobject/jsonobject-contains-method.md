---
title: "JsonObject.Contains(String) Method"
description: "Verifies if a JsonObject contains a property with a given key."
ms.author: solsen
ms.custom: na
ms.date: 07/07/2021
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# JsonObject.Contains(String) Method
> **Version**: _Available or changed with runtime version 1.0._

Verifies if a JsonObject contains a property with a given key.


## Syntax
```AL
Ok :=   JsonObject.Contains(Key: String)
```
## Parameters
*JsonObject*  
&emsp;Type: [JsonObject](jsonobject-data-type.md)  
An instance of the [JsonObject](jsonobject-data-type.md) data type.  

*Key*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
  


## Return Value
*Ok*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the object contains a property with the given key; otherwise, **false**.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[JsonObject Data Type](jsonobject-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)