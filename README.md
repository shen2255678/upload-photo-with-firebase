# upload-photo-with-firebase
此app含有會員系統並可將(gps定位、圖片/備註等)資訊上傳至firebase

* 拍完照上傳完會將此張照片於手機內自動刪除
# Test Run
Just putting these basic steps to help starters:

1. `File > Open` choose project folder and let android studio download supportive libraries.
2. `Build > Clean Project` and `Build > Rebuild Project`
3. If everything goes alright, you can start testing
4. In case or any error, check Build and Logcat tab for details
# Connect firebase
Firebase Storage Image/text Upload(https://firebase.google.com/docs/storage/android/start) 
(https://www.google.com "Google 的首頁")
1.`
2.
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
# About Project


