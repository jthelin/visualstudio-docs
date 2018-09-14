---
title: "IDebugCustomAttribute | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugCustomAttribute"
helpviewer_keywords: 
  - "IDebugCustomAttribute interface"
ms.assetid: c5ae41e9-00b9-4cca-871d-b8de9ef390d1
caps.latest.revision: 14
ms.author: "gregvanl"
manager: "ghogen"
---
# IDebugCustomAttribute
[!INCLUDE[vs2017banner](../../../includes/vs2017banner.md)]

The latest version of this topic can be found at [IDebugCustomAttribute](https://docs.microsoft.com/visualstudio/extensibility/debugger/reference/idebugcustomattribute).  
  
This interface represents a custom attribute, and it can provide the name, parent, and class type of the attribute.  
  
## Syntax  
  
```  
IDebugCustomAttribute : IUnknown  
```  
  
## Notes for Implementers  
 A symbol provider implements this interface in order to support custom attributes associated with a symbol. It is typically implemented on its own object.  
  
## Notes for Callers  
 A call to [Next](../../../extensibility/debugger/reference/ienumdebugcustomattributes-next.md) returns this interface. A call to the [EnumCustomAttributes](../../../extensibility/debugger/reference/idebugcustomattributequery2-enumcustomattributes.md) method returns the [IEnumDebugCustomAttributes](../../../extensibility/debugger/reference/ienumdebugcustomattributes.md) interface.  
  
## Methods in Vtable Order  
 The following table shows the methods of `IDebugCustomAttribute`.  
  
|Method|Description|  
|------------|-----------------|  
|[GetParentField](../../../extensibility/debugger/reference/idebugcustomattribute-getparentfield.md)|Gets the field to which the current attribute is attached.|  
|[GetAttributeTypeField](../../../extensibility/debugger/reference/idebugcustomattribute-getattributetypefield.md)|Gets the custom attribute class type.|  
|[GetName](../../../extensibility/debugger/reference/idebugcustomattribute-getname.md)|Gets the name of the custom attribute.|  
|[GetAttributeBytes](../../../extensibility/debugger/reference/idebugcustomattribute-getattributebytes.md)|Gets the attribute information as a blob of bytes.|  
  
## Remarks  
 A custom attribute is a structure for C# that supplies custom metadata associated with a particular class or method.  
  
## Requirements  
 Header: sh.h  
  
 Namespace: Microsoft.VisualStudio.Debugger.Interop  
  
 Assembly: Microsoft.VisualStudio.Debugger.Interop.dll  
  
## See Also  
 [Symbol Provider Interfaces](../../../extensibility/debugger/reference/symbol-provider-interfaces.md)   
 [IDebugField](../../../extensibility/debugger/reference/idebugfield.md)   
 [IDebugCustomAttributeQuery2](../../../extensibility/debugger/reference/idebugcustomattributequery2.md)   
 [IEnumDebugCustomAttributes](../../../extensibility/debugger/reference/ienumdebugcustomattributes.md)
