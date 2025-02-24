---
title: "HttpHeaders.Contains(String) Method"
description: "Checks if the specified header exists in the HttpHeaders collection."
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
# HttpHeaders.Contains(String) Method
> **Version**: _Available or changed with runtime version 1.0._

Checks if the specified header exists in the HttpHeaders collection.


## Syntax
```AL
Result :=   HttpHeaders.Contains(Name: String)
```
## Parameters
*HttpHeaders*  
&emsp;Type: [HttpHeaders](httpheaders-data-type.md)  
An instance of the [HttpHeaders](httpheaders-data-type.md) data type.  

*Name*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
The specific header.  


## Return Value
*Result*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the specified header exists in the collection; otherwise **false**.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[HttpHeaders Data Type](httpheaders-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)