<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

Spline chart library for Flutter. Spline chart is a line chart that uses curves instead of straight lines.

## Features

![Screenshot 1](https://raw.githubusercontent.com/medicaljoyworks/spline_chart/main/doc/images/screenshot1.png)
![Screenshot 2](https://raw.githubusercontent.com/medicaljoyworks/spline_chart/main/doc/images/screenshot2.png)
![Screenshot 3](https://raw.githubusercontent.com/medicaljoyworks/spline_chart/main/doc/images/screenshot3.png)

## Usage

Import the Spline Chart package and use the SplineChart widget.

```dart
import 'package:spline_chart/spline_chart.dart';

SplineChart(
  values: {0:10,15:30,50:10,44:100,80:50,100:90},
  verticalLineEnabled: true,
  verticalLinePosition: 90.0,
  verticalLineStrokeWidth: 2.0,
  verticalLineText: "The middle",
  drawCircles: true,
  circleRadius: 5,
  width: 320,
  height: 400,
)
```

## Additional information

This plugin is developed by [Medical Joyworks](https://www.medicaljoyworks.com/).