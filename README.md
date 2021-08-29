# r_dart_library
![dart](https://img.shields.io/badge/language-dart-orange.svg) [![pub package](https://img.shields.io/pub/v/r_dart_library.svg)](https://pub.dartlang.org/packages/r_dart_library) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A core library of R class which is generated by [Flr(Flutter-R)](https://github.com/Fly-Mix/flr-cli) in flutter project.

## dependency relationship table

Because the Flutter SDK is currently in an unstable state, so I create the following dependency relationship table for developer to select the correct version of `r_dart_library` based on the relationship table and the Flutter SDK version of Flutter project.

由于Flutter SDK目前处于不稳定的状态，所以我创建了下面这个依赖版本关系表，让开发者根据这个关系表和Flutter项目的Flutter SDK版本选择`r_dart_library`的正确版本。

| r_dart_library version | requires Flutter SDK version | requires Dart SDK version |
| ---------------------- | ---------------------------- | ---------------------- |
| [0.1.0, 0.1.1]                  | <1.10.15                     | <2.12.0 |
| [0.2.0, 0.2.1]                  | >=1.10.15                    | <2.12.0 |
| [0.4.0] | >=1.10.15 | >=2.12.0 |

## use this package as a library

1. Depend on it
	
	Add this to your package's pubspec.yaml file:
	
	```yaml
	dependencies:
	  r_dart_library:
	    git:
	      url: https://github.com/cqzhong/r_dart_library.git
	      ref: 0.1.0
	```
	
2. Install it
   You can install packages from the command line with Flutter:

   ```shell
   flutter pub get
   ```

   Alternatively, your editor might support flutter pub get. Check the docs for your editor to learn more.

3. Import it

  Now in your Dart code, you can use:

  ```dart
  import 'package:r_dart_library/asset_svg.dart';
  ```

