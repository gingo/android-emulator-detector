Android EmulatorDetector
=========================

Small utility for detecting if your app is running on emulator, or real device.

Usage is as simple as calling:

```java
EmulatorDetector.isEmulator();
```

You can print all parameters from `android.os.Build` used to determine if you are on device or emulator:

```java
EmulatorDetector.logcat();
```

The same as String:

```java
EmulatorDetector.getDeviceListing();
```

Installation
-------------

Download jar archive and attach it as a project library:

https://github.com/gingo/android-emulator-detector/blob/master/emulator_detector_v0.1.0.jar