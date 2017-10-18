## GPSLocation
Get GPS location with Android Studio

## On the device
Android version: more than 2.3.3(API 10)
Installed Google Play 

## Installed Google Play services on Android Studio

## add the following line in file build.gradle, and click on Sync Project with Gradle Files
compile 'com.google.android.gms:play-services-location:8.1.0'

## Result
<p align="center"/>
<img src="pics/result.jpg" height="500" />
/***note that this program get GPS location when the program starts; it will not update the location until finishing the program***/
