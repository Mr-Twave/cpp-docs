---
title: "Error embedding Win32 manifest: Option -win32manifest conflicts with -nowin32manifest | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "vbc2033"
  - "bc2033"
helpviewer_keywords: 
  - "BC2033"
ms.assetid: e921b34a-1ab3-4ba0-81b3-e45c62de4718
caps.latest.revision: 4
author: "stevehoag"
ms.author: "shoag"
manager: "wpickett"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# Error embedding Win32 manifest: Option /win32manifest conflicts with /nowin32manifest
The Visual Basic compiler has been passed both a `/win32manifest` compiler option and a `/nowin32manifest` compiler option. Only one of these options can be passed to the Visual Basic compiler.  
  
 **Error ID:** BC2033  
  
### To correct this error  
  
1.  Remove either the `/win32manifest` compiler option or the `/nowin32manifest` compiler option.  
  
## See Also  
 [/win32manifest (Visual Basic)](/dotnet/visual-basic/reference/command-line-compiler/win32manifest)   
 [/nowin32manifest (Visual Basic)](/dotnet/visual-basic/reference/command-line-compiler/nowin32manifest)   
 [Visual Basic Command-Line Compiler](/dotnet/visual-basic/reference/command-line-compiler/index)