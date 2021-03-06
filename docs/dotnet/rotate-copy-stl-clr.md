---
title: "rotate_copy (STL/CLR) | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-cli"]
ms.topic: "reference"
f1_keywords: ["cliext::rotate_copy"]
dev_langs: ["C++"]
helpviewer_keywords: ["rotate_copy function [STL/CLR]"]
ms.assetid: ed697552-130f-474f-9ab6-133332bb2587
author: "mikeblome"
ms.author: "mblome"
ms.workload: ["cplusplus", "dotnet"]
---
# rotate_copy (STL/CLR)
Exchanges the elements in two adjacent ranges within a source range and copies the result to a destination range.  
  
## Syntax  
  
```  
template<class _FwdIt, class _OutIt> inline  
    _OutIt rotate_copy(_FwdIt _First, _FwdIt _Mid, _FwdIt _Last,  
        _OutIt _Dest);  
```  
  
## Remarks  
 This function behaves the same as the C++ Standard Library function `rotate_copy`. For more information, see [rotate_copy](../standard-library/algorithm-functions.md#rotate_copy).  
  
## Requirements  
 **Header:** \<cliext/algorithm>  
  
 **Namespace:** cliext  
  
## See Also  
 [algorithm (STL/CLR)](../dotnet/algorithm-stl-clr.md)