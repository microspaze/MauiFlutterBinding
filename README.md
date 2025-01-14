# Maui Flutter Binding

An example of how to integrate flutter with .NET MAUI. 

## Table of contents

- [Requirements](#requirements)
- [Usage](#usage)
- [More](#more)

## Requirements

- Xcode
- Android Studio
- Visual Studio for Mac or VSCode
- [Objective Sharpie](https://learn.microsoft.com/en-us/xamarin/cross-platform/macios/binding/objective-sharpie/get-started)

## Usage

### .NET MAUI 

Build and run the project directly. The framework are already build.

### Android Binding

Run *build.sh* in Android.Native to rebuild/modify the binding framework. You can open the binding project with android studio to test. There is an android app there. Copy the jars that are needed to Android.Binding. 

### iOS Binding

Run *build.sh* in iOS.Native to rebuild/modify the binding framework. Sharpie does make an error but the file is generated correctly. You can open the binding xcodeproj with xcode to test. Copy the xcframework that are neaded to iOS.Binding. 

### Flutter build
Read the doc to embedded flutter at [Add Flutter to an existing app](https://docs.flutter.dev/add-to-app). The command are :

```
flutter build ios-framework
flutter build aar
```

The release App.xcframework does not work on the simulator. To make it work replace the ios-arm64\_x86\_64-simulator part from the debug build. You can do it using [flutter_app/build.sh](https://github.com/cl3m/MauiFlutterBinding/blob/master/flutter_app/build.sh).


## More

* [MauiPDFViewerBinding](https://github.com/cl3m/MauiPDFViewerBinding)
* [Add Flutter to an existing app](https://docs.flutter.dev/add-to-app)
* [Build MAUI control for AutoNavi Map](https://github.com/kinfey/AMapMAUIControls)
* [Lottie Maui](https://github.com/Csaba8472/LottieMaui)
* [Xamarin.Binding.Helper](https://github.com/Redth/Xamarin.Binding.Helpers)
* [Xamarin Encapsulate Native Sample](https://github.com/Redth/XamarinEncapsulateNativeSample)
