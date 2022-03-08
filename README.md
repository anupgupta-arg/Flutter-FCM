# fcm_msg

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Used Library:

- cupertino_icons: ^1.0.2
- firebase_core: ^1.13.1
- flutter_local_notifications: ^9.4.0
- firebase_messaging: ^11.2.8
- http: ^0.13.4

## Do some miner Changes in 
> Android -> app -> build.gradle

```
 defaultConfig {
        // TODO: Specify your own unique Application ID (https://developer.android.com/studio/build/application-id.html).
        applicationId "<Use your app id>"               // use your App id 
        // minSdkVersion flutter.minSdkVersion          // need to remove this line 
        minSdkVersion 19                                // Add this 
        targetSdkVersion flutter.targetSdkVersion
        versionCode flutterVersionCode.toInteger()
        versionName flutterVersionName                  // Add this 
    }
```
```
apply plugin: 'com.google.gms.google-services'
```

> Android -> build.gradle

```
 dependencies {
        classpath 'com.android.tools.build:gradle:4.1.0'
        classpath "org.jetbrains.kotlin:kotlin-gradle-plugin:$kotlin_version"
        classpath 'com.google.gms:google-services:4.3.10'     // Add this 
    }
```



  
  

