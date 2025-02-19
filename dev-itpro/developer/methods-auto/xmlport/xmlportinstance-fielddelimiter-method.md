---
title: "Xmlport.FieldDelimiter([String]) Method"
description: "Gets and sets the FiledDelimiter used when running, importing or exporting the XmlPort."
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
# Xmlport.FieldDelimiter([String]) Method
> **Version**: _Available or changed with runtime version 1.0._

Gets and sets the FiledDelimiter used when running, importing or exporting the XmlPort.


## Syntax
```AL
[Delimiter := ]  Xmlport.FieldDelimiter([Delimiter: String])
```
> [!NOTE]
> This method can be invoked using property access syntax.
## Parameters
*Xmlport*  
&emsp;Type: [Xmlport](xmlport-data-type.md)  
An instance of the [Xmlport](xmlport-data-type.md) data type.  

*[Optional] Delimiter*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
The new value of the FieldDelimiter.  


## Return Value
*[Optional] Delimiter*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
The FieldDelimiter used when running, importing or exporting the XmlPort.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[Xmlport Data Type](xmlport-data-type.md)  
[FieldDelimiter Property](../../properties/devenv-fielddelimiter-property.md)   
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)