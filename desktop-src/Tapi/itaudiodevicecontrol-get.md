---
Description: The Get method retrieves the value of a given audio device property.
ms.assetid: 34cb3f3e-be4a-49e0-bf7d-6915906e2368
title: ITAudioDeviceControl::Get method (Ipmsp.h)
ms.topic: reference
ms.date: 05/31/2018
---

# ITAudioDeviceControl::Get method

\[ This method is not available for use in Windows Vista, Windows Server 2008, and subsequent versions of the operating system. The RTC Client API provides similar functionality.\]

The **Get** method retrieves the value of a given [**audio device property**](audiodeviceproperty.md).

## Syntax


```C++
HRESULT get_Call(
  [out] ITCallInfo **ppCall
);
```



## Parameters

<dl> <dt>

*Property* \[in\]
</dt> <dd>

Member of the [**AudioDeviceProperty**](audiodeviceproperty.md) enum.

</dd> <dt>

*plValue* \[out\]
</dt> <dd>

Value of the input *Property*.

</dd> <dt>

*plFlags* \[out\]
</dt> <dd>

Value of the [**TAPIControlFlags**](tapicontrolflags.md) enum indicating how the *Property* value is controlled.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                                   | Description                                                     |
|-----------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>          | Method succeeded.<br/>                                    |
| <dl> <dt>**E\_OUTOFMEMORY**</dt> </dl> | Insufficient memory exists to perform the operation.<br/> |



 

## Requirements



|                         |                                                                                      |
|-------------------------|--------------------------------------------------------------------------------------|
| TAPI version<br/> | Requires TAPI 3.1<br/>                                                         |
| Header<br/>       | <dl> <dt>Ipmsp.h</dt> </dl>   |
| Library<br/>      | <dl> <dt>Uuid.lib</dt> </dl>  |
| DLL<br/>          | <dl> <dt>Tapi3.dll</dt> </dl> |



## See also

<dl> <dt>

[**ITAudioDeviceControl**](itaudiodevicecontrol.md)
</dt> <dt>

[**TAPIControlFlags**](tapicontrolflags.md)
</dt> <dt>

[**AudioDeviceProperty**](audiodeviceproperty.md)
</dt> </dl>

 

 




