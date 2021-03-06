---
-api-id: M:Windows.UI.Xaml.Media.Imaging.BitmapSource.SetSource(Windows.Storage.Streams.IRandomAccessStream)
-api-type: winrt method
---

<!-- Method syntax
public void SetSource(Windows.Storage.Streams.IRandomAccessStream streamSource)
-->

# Windows.UI.Xaml.Media.Imaging.BitmapSource.SetSource

## -description
Sets the source image for a [BitmapSource](bitmapsource.md) by accessing a stream. Most callers should use [SetSourceAsync](bitmapsource_setsourceasync.md) instead.

## -parameters
### -param streamSource
The stream source that sets the image source value.

## -remarks
Calling [SetSource](bitmapsource_setsource.md) rather than [SetSourceAsync](bitmapsource_setsourceasync.md) has the potential to block the UI thread until the image source file is returned and processed. It is for this reason that we generally recommend calling [SetSourceAsync](bitmapsource_setsourceasync.md) instead of calling [SetSource](bitmapsource_setsource.md).

In low memory situations (most likely on lower-memory phones), it is possible for an exception to be raised with the message "The image is unrecognized" and an HRESULT of 0x88982F60. While this exception ordinarily indicates bad data, if your app is close to its memory limit then the cause of the exception is likely to be low memory. In that case, we recommend that you free memory and try again.

## -examples

## -see-also
[SetSourceAsync](bitmapsource_setsourceasync.md), [UriSource](bitmapimage_urisource.md), [Imaging](http://msdn.microsoft.com/library/3fd2aa71-ef67-47b2-9332-3ffa5d3703ea)