---
description: "Determines if registry queries can be used to locate symbol search paths."
title: "IDiaLoadCallback::RestrictRegistryAccess | Microsoft Docs"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "IDiaLoadCallback::RestrictRegistryAccess method"
ms.assetid: de4760c3-a746-4bab-8065-1388fed31b67
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
  - "multiple"
---
# IDiaLoadCallback::RestrictRegistryAccess

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Determines if registry queries can be used to locate symbol search paths.

## Syntax

```C++
HRESULT RestrictRegistryAccess();
```

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## Remarks
 Any return code other than `S_OK` prevents querying the registry for symbol search paths.

## See also
- [IDiaLoadCallback2](../../debugger/debug-interface-access/idialoadcallback2.md)
