# conviva-android-brightcove

## Conviva brightcove module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-brightcove-sdk:4.0.9'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])
    
## Support Android Version    
    Android 12

## Support Brightcove SDK Version    
    Brightcove 8.1.0

## Support Conviva Android CoreSDK Version
    Conviva Android CoreSDK v4.0.31
    https://github.com/Conviva/conviva-android-coresdk/releases/tag/v4.0.31

## Note:  

* Refer https://pulse.conviva.com/learning-center/content/main/main.htm for integration guidelines.
