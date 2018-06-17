---
Description: The following Winternl.h definition is the static memory address of the active Terminal Services console session ID. This active console session ID is not defined in versions of the Microsoft Windows operating system earlier than Windows XP.
ms.assetid: f3022ab8-60ea-490b-a87d-cc1afc99d26f
title: Getting the Active Console Session ID
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Getting the Active Console Session ID

The following Winternl.h definition is the static memory address of the active Terminal Services console session ID. This active console session ID is not defined in versions of the Microsoft Windows operating system earlier than Windows XP.

> [!Note]  
> This definition may change in future releases of Windows. To ensure that your application will continue to run correctly in the future, your application must call [**WTSGetActiveConsoleSessionId**](https://msdn.microsoft.com/en-us/library/Aa383835(v=VS.85).aspx).

 

``` syntax
#define INTERNAL_TS_ACTIVE_CONSOLE_ID    
        (*((volatile ULONG*)(0x7ffe02d8)))
```

 

 


