# Firebase Messaging


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



  
  

