# upload-photo-with-firebase
This is one of many ways to create a photo upload service using Firebase and Android. I belive there is a lot of more improvement work to be done to handle errors in the server-side.

This repo contains both the Android app and the firebase sources, they are in two separaed folders.

The folders are:

* App - This is the Android App
* Server - Firebase
# Test Run
Just putting these basic steps to help starters:

1.File > Open choose project folder and let android studio download supportive libraries.
2.Build > Clean Project and Build > Rebuild Project
3.If everything goes alright, you can start testing
4.In case or any error, check Build and Logcat tab for details

# Permissions
Followings are permissions required for all the mentioned features to work.
```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.CAMERA"/>
```
`INTERNET` permission is required to access online content and `WRITE_EXTERNAL_STORAGE`+`CAMERA` permissions to take photo from camera and save it to gallery
# Know bugs
```
22/09/19 - Camera not working in API 29
```
