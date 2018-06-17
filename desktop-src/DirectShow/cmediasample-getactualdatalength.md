---
Description: The GetActualDataLength method retrieves the length of the valid data in the buffer. This method implements the IMediaSample::GetActualDataLength method.
ms.assetid: bdb8c2b9-7be4-494b-bb96-34a9936d4a2f
title: CMediaSample.GetActualDataLength method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CMediaSample.GetActualDataLength method

The `GetActualDataLength` method retrieves the length of the valid data in the buffer. This method implements the [**IMediaSample::GetActualDataLength**](https://msdn.microsoft.com/en-us/library/Dd407007(v=VS.85).aspx) method.

## Syntax


```C++
LONG GetActualDataLength();
```



## Parameters

This method has no parameters.

## Return value

Returns the length of the valid data, in bytes.

## Remarks

The [**CMediaSample::m\_lActual**](cmediasample-m-lactual.md) member variable specifies this property.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Amfilter.h (include Streams.h)</dt> </dl>                                                                                  |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CMediaSample Class**](cmediasample.md)
</dt> </dl>

 

 



