# conviva-android-brightcove

## Conviva brightcove module can be included in two ways in any Android app projects.

* Gradle dependency
* Offline library

## Gradle dependency
    Add the following line to app's build.gradle file.
    
    implementation 'com.conviva.sdk:conviva-brightcove-sdk:4.0.1.1'
    
## Offline library
    Place the Conviva library in app's 'lib' folder and add the following line to app's build.gradle file.
    
    implementation fileTree(dir: 'libs',include:['*.aar'])
    
    
## Note:  

* Refer https://community.conviva.com/ for integration guidelines.
