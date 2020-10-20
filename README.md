# conviva-android-brightcove

## Conviva brightcove module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-brightcove-sdk:4.0.2.38'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])
    
## Support Android Version    
    Android 11

## Support Brightcove SDK Version    
    Brightcove 6.14.0

## Support Conviva Android CoreSDK Version
    Conviva Android CoreSDK v4.0.10.141
    https://github.com/Conviva/conviva-android-coresdk/releases/tag/v4.0.10.141

## Note:  

* Refer https://community.conviva.com/ for integration guidelines.
