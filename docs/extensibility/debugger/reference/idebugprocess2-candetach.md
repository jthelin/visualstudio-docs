---
title: "IDebugProcess2::CanDetach | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: 
  - "vs-ide-sdk"
ms.topic: "conceptual"
f1_keywords: 
  - "IDebugProcess2::CanDetach"
helpviewer_keywords: 
  - "IDebugProcess2::CanDetach"
ms.assetid: 2830f7c3-69fb-474a-97b8-5b869e38d546
author: "gregvanl"
ms.author: "gregvanl"
manager: douge
ms.workload: 
  - "vssdk"
---
# IDebugProcess2::CanDetach
Determines if the session debug manager (SDM) can detach the process.  
  
## Syntax  
  
```cpp  
HRESULT CanDetach(  
   void  
);  
```  
  
```csharp  
int CanDetach();  
```  
  
## Return Value  
 If successful, returns `S_OK.` Returns `S_FALSE` if the debugger cannot detach from the process. Otherwise, returns an error code.  
  
## See Also  
 [CanDetach](../../../extensibility/debugger/reference/idebugprogram2-candetach.md)   
 [IDebugProcess2](../../../extensibility/debugger/reference/idebugprocess2.md)