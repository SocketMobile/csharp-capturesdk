# Changelog

This file tracks released versions of the C# CaptureSDK.

## Version 1.7.34.67

- We are back on Github 🚀
- Updated CaptureSDK release publicly on [nuget.org](https://www.nuget.org/packages/SocketMobile.Capture)
- Updated documentation on scanner configuration and pairing per platform
- Updated documentation on unsupported D600 and S370 devices on Windows
- Fixed Bluetooth Low Energy Manager device removal event when the Bluetooth is switched off

## Version 1.7.54.884

- Last version to support Xamarin
- Updated native iOS and Android SDKs, see [Developer Portal](https://www.socketmobile.dev)
- Updated NuGet package released on [nuget.org](https://www.nuget.org/packages/SocketMobile.Capture)
- Added support for M963 device 
- Fixed connection dropping after 30 seconds for projects targeting .NET 6 and above
- Updated documentation on S370 device about getting a double device arrival event

## Version 1.7.68.40

- Updated NuGet package released on [nuget.org](https://www.nuget.org/packages/SocketMobile.Capture)
- Removed Xamarin support
- Added device properties in CaptureHelper
  - [Get/Set]ThemeSelectionAsync() method. Retrieve or Set the UI theme for devices like S550 or S370
  - SetFactoryResetAsync() method. Factory resets a Bluetooth Low Energy device like S320, S370, S550
  - [Get/Set]TimersTimeoutAsync() method. Retrieve or Set the auto lock and power off timers

## Version 1.7.83.246

- Updated NuGet package released on [nuget.org](https://www.nuget.org/packages/SocketMobile.Capture)
- Fixed `SetTimersTimeoutAsync()` method by adding the auto lock parameter
  - Added Timer documentation [here](https://docs.socketmobile.dev/capture/csharp/en/latest/topicsTimers.html)
- Fixed SocketCam's stability on Windows (UWP)
  - Camera switch
  - No Camera detected
  - USB Camera support, check [documentation](https://docs.socketmobile.dev/capture/csharp/en/latest/topicsSocketCam.html) under SocketCam->Setup->Windows (UWP)->Note
- Updated Native iOS CaptureSDK from version 1.9.133 to version 1.9.139
  - We have updated SwiftDecoder to 6.2.3 that fixes the [signature error](https://github.com/SocketMobile/swift-package-capturesdk/issues/28)
- Added the NFC Tag ID, `TagIdData`, in the `CaptureDecodedData` received from the `DecodedData` event (available on iOS and Windows)

## Version 1.7.112.395

- Updated NuGet package released on [nuget.org](https://www.nuget.org/packages/SocketMobile.Capture)
- Added SocketCam C820 support to MAUI
- Fixed symbology availability across different camera usages. Symbologies are now consistent across all devices
