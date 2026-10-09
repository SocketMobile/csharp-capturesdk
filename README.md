# C# CaptureSDK Version 2.1.20.64 Windows, Android and iOS Support

## PLEASE UPDATE YOUR CAPTURESDK TO 2.1

As we're transitioning our scanners to Bluetooth Low Energy and improving our CaptureSDKs, we recommend you to update to the latest version 2.1 to be compatible and benefit from all our latest features.

Versions prior 2.1.x will be removed from our repositories as of 1st of December 2026 for all platforms.

Please visit [our brand new Developer Portal and documentation](https://socketmobile.dev/docs/) to see the latest versions of our CaptureSDK.

## CaptureSDK
The C# CaptureSDK is available publicly on [NuGet](https://www.nuget.org/packages/SocketMobile.Capture).

**[Documentation](https://socketmobile.dev/docs)** | **[Sample App](https://github.com/SocketMobile/capture_maui_sdk_sample)** | **[Changelog](CHANGELOG.md)**

Socket Mobile is a leading innovator of data capture and delivery solutions for enhanced productivity.

CaptureSDK is the easiest solution for adding barcode scanning capability to a Windows, Android or iOS application.

The Socket Mobile barcode scanner is an ergonomic, fast and accurate solution to a variety of data entry scenarios.

This SDK is very easy to integrate to an application without any requirement to follow a specific design architecture.

Integration into an application can be done in as little as 10 minutes!

**For the smoothest integration**, start at the [Developer Portal](https://socketmobile.dev/docs), which takes you straight to the CaptureSDK documentation, then follow the guide to get the SDK running in your app.

## Requirement - Socket Mobile Companion

Socket Mobile Companion is a standalone app that handles the discovery and selection of the reader to connect to, and guides the user through the whole connection process. Once a reader is connected, your app receives its data through CaptureSDK.

On Windows and Android, installing Companion also installs the components CaptureSDK needs to manage Bluetooth communication with the readers, which is why it is required on those platforms.

| Platform | Companion   | Notes                                                                                       | Download                                                                                    |
| :------- | :---------- | :------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------ |
| Windows  | Required    | Must be installed on the host PC.                                                           | [GitHub Releases](https://github.com/SocketMobile/companion-windows/releases/latest)        |
| Android  | Required    | Must be installed on the device.                                                            | [Google Play](https://play.google.com/store/apps/details?id=com.socketmobile.companion)     |
| iOS      | Recommended | Recommended for pairing scanners.                                   | [App Store](https://apps.apple.com/app/socket-mobile-companion/id1175638950)             |

## Devices Compatibility and CaptureSDK Versions

|                    Devices                     | < 2.0 | 2.0 | 2.1 |
| :--------------------------------------------: | :---: | :-: | :-: |
|                    **S320**                    |  ✅  | ✅ | ✅ |
|                 **M930/M940**                  |  ✅  | ✅ | ✅ |
|    **SocketCam C820 (Windows[UWP/MAUI-NET9])** |  ✅  | ✅ | ✅ |
|          **SocketCam C860 (Android-iOS)**      |  ✅  | ✅ | ✅ |
|          **SocketCam C820 (Android-iOS)**      |  ✅  | ✅ | ✅ |
|               **S720/D720/S820**               |  ✅  | ✅ | ✅ |
|             **D600 (Android-iOS)**             |  ✅  | ✅ | ✅ |
|    **S550, and all older barcode scanners**    |  ✅  | ✅ | ✅ |
|                    **S370**                    |  ✅  | ✅ | ✅ |
|                    **M963**                    |  ✅  | ✅ | ✅ |
|                    **S721**                    |  ✅  | ✅ | ✅ |
|           **Magic Dock and SM Link**           |  ❌  | ❌ | ✅ |

Note: Bluetooth LE devices (such as the D600, S550, S320 and S370) support also relies on the Companion version for Windows and Android.
For instance, **the D600 is not supported by Windows Companion**.
