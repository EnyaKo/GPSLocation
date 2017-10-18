Get GPS location with Android Studio

# On the Device
Android version: more than 2.3.3(API 10)
Installed Google Play 

# On Android Studio

### Installed Google Play services on Android Studio

### add the following line in file build.gradle, and click on Sync Project with Gradle Files
compile 'com.google.android.gms:play-services-location:8.1.0'

# Result
<p align="center"/>
<img src="pic/result.jpg" height="500" />

/***note that this program get GPS location when the program starts; it will not update the location until finishing the program***/
