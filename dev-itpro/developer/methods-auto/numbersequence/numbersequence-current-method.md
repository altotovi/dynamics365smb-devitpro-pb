---
title: "NumberSequence.Current(String [, Boolean]) Method"
description: "Gets the current value from the number sequence, without doing any increment."
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
# NumberSequence.Current(String [, Boolean]) Method
> **Version**: _Available or changed with runtime version 4.0._

Gets the current value from the number sequence, without doing any increment. The value is retrieved out of transaction. The value will not be returned on transaction rollback.


## Syntax
```AL
Current :=   NumberSequence.Current(Name: String [, CompanySpecific: Boolean])
```
## Parameters
*Name*  
&emsp;Type: [String](/dynamics365/business-central/dev-itpro/developer/methods-auto/text/text-data-type)  
Specifies the name of the number sequence.  
*[Optional] CompanySpecific*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
Specifies if the number sequence is company-specific. Default is true.  


## Return Value
*Current*  
&emsp;Type: [BigInteger](../biginteger/biginteger-data-type.md)  
Returns the current value from number sequence.


[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Example
The following example gets the current value for the number sequence `MyNumberSequence`, which is not company specific.
 
```al
number := NumberSequence.Current('MyNumberSequence', false);
```

## See Also
[NumberSequence Data Type](numbersequence-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)