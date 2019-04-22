This is a case study on Flutter, a new cross-platform mobile development framework.

## Overview
Flutter is an SDK developed by Google for fast and robust cross-platform mobile application development. It is an open-source project used in many applications, and it aims to allow designing and writing interfaces that function well, look sleek and are easy to code. Some of its core features include a fully customizable and flexible UI, a responsive interface, and integration with existing tools like Java, Kotlin, Objective C, and Swift code, platform APIs, as well as third-party SDKs.
To see further report on the case study, look under docs/

## Technology and Platform
### a.	Coding language

Flutter is written in Dart, a programming language also developed by Google. Dart is an object-oriented language which can be compiled to JavaScript or mobile application languages like Objective-C, Swift, Java and Kotlin. According to Flutter’s developers, Dart was "designed to be easy to write development tools for, well-suited to modern app development, and capable of high-performance implementations." Outside the scope of Flutter, Dart could be employed to build web and server applications.
Since Flutter debuted in 2017, had it been introduced today, Dart would still be a perfect candidate. First of all, Flutter is a Google project using primarily Google libraries and frameworks (such as Skia), an in-house language like Dart would facilitate integrations and developments by eliminating the barrier between language maintainer/developer and Flutter framework developer. While there exists other more established languages for creating applications, such as JavaScript for React Native, Dart has more features that could be used to create smooth UIs with animations and powerful rendering. Dart includes a rich type system, module system, native testing framework, and a native package manager. 

### b.	Build system: Flutter functions like a game engine. Instead of utilizing web view or relying on the device’s OEM widgets, Flutter renders every view component using its own high-performance rendering engine. This allows building applications with native-like performance characteristics. The engine’s C/C++ code is compiled with NDK on Android and LLVM on iOS. Any Dart code is AOT-compiled to native code during compilation.

In order to develop a Flutter application, users have two options.
1.	Visual Studio Code (or any IDEs with Flutter and Dart supports): Flutter codes could be compiled and run on the command line.
2.	Android Studio (with Flutter and Dart plug-ins)

###c.	Engine and Frameworks.

Engine: The engine’s C and C++ code is compiled with Android’s NDK or iOS’s LLVM. The Dart code (both the SDK and the App code) is ahead-of-time (AOT) compiled into native ARM library. This library is included in “runner” Android/IOS project, and combined into .apk or .ipa. When launched, the app loads the Flutter Library. Any rendering, input or event handling is delegated to the compiled Flutter and app code.
 

Framework: The Flutter framework contains everything you need to develop an app. Flutter apps look like native iOS or Android application with Cupertino theme for iOS, and Material for Android.
Flutter is heavily based on materials software design paradigm, a design model by Google. A basic unit in any Flutter application is called a widget. Flutter doesn’t have native controls or components. Flutter draws the UI output on a Skia Canvas. This reduces complexity drastically, as Flutter only has Widgets. Widgets are UI controls that you can use in your app. Your entire app will be made up of Stateless or Stateful Widgets. 

![Image of Architecture](docs/flutter_overview.jpg)

## Example Code 
1. To install flutter, follow instructions from the following link
https://flutter.dev/docs/get-started/install

2. To run this hello-world application, clone this repo & run
```
git clone https://github.com/ec500-software-engineering/case-study-thaorell
cd flutter_app
flutter run
```