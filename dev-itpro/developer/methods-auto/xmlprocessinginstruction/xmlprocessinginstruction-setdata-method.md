---
title: "XmlProcessingInstruction.SetData(String) Method"
description: "Sets the content of the processing instruction, excluding the target."
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
# XmlProcessingInstruction.SetData(String) Method
> **Version**: _Available or changed with runtime version 1.0._

Sets the content of the processing instruction, excluding the target.


## Syntax
```AL
[Ok := ]  XmlProcessingInstruction.SetData(Value: String)
```
## Parameters
*XmlProcessingInstruction*  
&emsp;Type: [XmlProcessingInstruction](xmlprocessinginstruction-data-type.md)  
An instance of the [XmlProcessingInstruction](xmlprocessinginstruction-data-type.md) data type.  

*Value*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
The new content of the processing instruction, excluding the target.  


## Return Value
*[Optional] Ok*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the operation was successful; otherwise **false**.   If you omit this optional return value and the operation does not execute successfully, a runtime error will occur.  


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[XmlProcessingInstruction Data Type](xmlprocessinginstruction-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)