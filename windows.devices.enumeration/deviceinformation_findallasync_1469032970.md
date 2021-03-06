---
-api-id: M:Windows.Devices.Enumeration.DeviceInformation.FindAllAsync(System.String,Windows.Foundation.Collections.IIterable{System.String})
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Devices.Enumeration.DeviceInformationCollection> FindAllAsync(System.String aqsFilter, Windows.Foundation.Collections.IIterable<System.String> additionalProperties)
-->

# Windows.Devices.Enumeration.DeviceInformation.FindAllAsync

## -description
Enumerates [DeviceInformation](deviceinformation.md) objects matching the specified Advanced Query Syntax (AQS) device interface selector string and including the specified collection of properties.

## -parameters
### -param aqsFilter
An AQS device interface selector string that filters the [DeviceInformation](deviceinformation.md) objects to enumerate. Typically this string is retrieved from the **GetDeviceSelector** method of a class that interacts with devices. For example, [GetDeviceSelector](../windows.devices.portable/storagedevice_getdeviceselector.md) retrieves the string for the [StorageDevice](../windows.devices.portable/storagedevice.md) class.

### -param additionalProperties
An iterable list of additional properties to include in the [Properties](deviceinformation_properties.md) property of the [DeviceInformation](deviceinformation.md) objects in the enumeration results. For more info on what the properties represent, see [Device information properties](http://msdn.microsoft.com/library/4a4c2802-e674-4c04-8a6d-d7c1bbf1bd20).

## -returns
The object for managing the asynchronous operation.

## -remarks

## -examples

## -see-also
[FindAllAsync](deviceinformation_findallasync_326280522.md), [FindAllAsync(DeviceClass)](deviceinformation_findallasync_1653398836.md), [FindAllAsync(String)](deviceinformation_findallasync_1257462890.md)