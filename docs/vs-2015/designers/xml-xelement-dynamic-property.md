---
title: "Xml (XElement Dynamic Property) | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-csharp"
ms.tgt_pltfrm: ""
ms.topic: "article"
api_name: 
  - "XElement.Xml"
ms.assetid: 69ab2a33-4fe7-4cfa-97f8-eaf063decb18
caps.latest.revision: 4
author: gewarren
ms.author: gewarren
manager: "ghogen"
---
# Xml (XElement Dynamic Property)
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

The latest version of this topic can be found at [Xml (XElement Dynamic Property)](https://docs.microsoft.com/visualstudio/designers/xml-xelement-dynamic-property).  
  
Gets the unformatted XML content of the element.  
  
## Syntax  
  
```  
elem.Xml  
```  
  
## Property Value/Return Value  
 A <xref:System.String> that represents the unformatted XML content of the element.  
  
## Remarks  
 This property is equivalent to the <xref:System.Xml.Linq.XNode.ToString%28System.Xml.Linq.SaveOptions%29> method of the <xref:System.Xml.Linq.XNode?displayProperty=fullName> class, with the `SaveOptions` parameter set to <xref:System.Xml.Linq.SaveOptions>.  
  
## See Also  
 [XElement Class Dynamic Properties](../designers/xelement-class-dynamic-properties.md)   
 [Value](../designers/value-xelement-dynamic-property.md)


