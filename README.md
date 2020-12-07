# mobile

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

//TODO security rules is left to configure

### run app from main.dart

### build apk file

- `flutter clean`
- `flutter pub upgrade`
- `flutter pub cache repair`
- `flutter build apk`

## copy file from PC to device

- simply drag and drop `build/app/output/flutter-apk/app-release.apk` to folder in `file manager` not `file`

## figured out how install apk wirelessly from vscode

- `adb connect device_ip:5555` is required
- bottom right conner there is device detail of device adb is connected to
- after chosen
  -click on run form `main.dart`

## how to open two windows of same workspace in vscode

(Command + shift + P in Mac), then type dupl

## hot reload in multiple devices
