---
title: "IDebugProperty2::GetReference | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: reference
f1_keywords:
  - "IDebugProperty2::GetReference"
helpviewer_keywords:
  - "IDebugProperty2::GetReference method"
ms.assetid: 2fa97d9b-c3d7-478e-ba5a-a933f40a0103
author: "gregvanl"
ms.author: "gregvanl"
manager: jillfra
ms.workload:
  - "vssdk"
---
# IDebugProperty2::GetReference
Returns a reference to the property's value.

## Syntax

```cpp
HRESULT GetReference(
   IDebugReference2** ppReference
);
```

```csharp
int GetReference(
   out IDebugReference2 ppReference
);
```

#### Parameters
 `ppRererence`

 [out] Returns an [IDebugReference2](../../../extensibility/debugger/reference/idebugreference2.md) object representing a reference to the property's value.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code, typically `E_NOTIMPL` or `E_GETREFERENCE_NO_REFERENCE`.

## See Also
- [IDebugProperty2](../../../extensibility/debugger/reference/idebugproperty2.md)
- [IDebugReference2](../../../extensibility/debugger/reference/idebugreference2.md)