---
title: "steady_clock struct | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: ["cpp-standard-libraries"]
ms.topic: "reference"
f1_keywords: ["chrono/std::chrono::steady_clock"]
dev_langs: ["C++"]
ms.assetid: 970d12ec-fc80-4391-a2f7-b57b2aec668d
author: "corob-msft"
ms.author: "corob"
ms.workload: ["cplusplus"]
---
# steady_clock struct

Represents a `steady` clock.

## Syntax

```cpp
struct steady_clock;
```

## Remarks

On Windows, steady_clock wraps the QueryPerformanceCounter function.

A clock is *monotonic* if the value that is returned by a first call to `now()` is always less than or equal to the value that is returned by a subsequent call to `now()`.

A clock is *steady* if it is *monotonic* and if the time between clock ticks is constant.

High_resolution_clock is a typdef for steady_clock.

## Public functions

|Function|Description|
|--------------|-----------------|
|now|Returns the current time as a time_point value.|

## Public Constants

|Name|Description|
|----------|-----------------|
|`system_clock::is_steady`|Holds `true`. A `steady_clock` is *steady*.|

## Requirements

**Header:** \<chrono>

**Namespace:** std::chrono

## See also

[Header Files Reference](../standard-library/cpp-standard-library-header-files.md)<br/>
[\<chrono>](../standard-library/chrono.md)<br/>
[system_clock Structure](../standard-library/system-clock-structure.md)<br/>
