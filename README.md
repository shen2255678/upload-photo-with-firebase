# upload-photo-with-firebase 簡介
是一款用於在Android的app可上傳照片(拍照或從相簿文件中選擇)並可將(gps定位、備註等)資訊上傳至firebase
* 會員帳號註冊系統
* 拍完照上傳完會將此張照片於手機內自動刪除
* 支援從相冊選擇圖片
* 支援gps定位
# Test Run
Just putting these basic steps to help starters:

1. `File > Open` choose project folder and let android studio download supportive libraries.
2. `Build > Clean Project` and `Build > Rebuild Project`
3. If everything goes alright, you can start testing
4. In case or any error, check Build and Logcat tab for details
# Connect firebase 
[Firebase Storage Image/Text Upload and setting](https://firebase.google.com/docs/storage/android/start)

1.'Tools >Firebase' in Android Studio

# Permissions
Followings are permissions required for all the mentioned features to work.
```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.CAMERA"/>
```
`INTERNET` permission is required to access online content and `WRITE_EXTERNAL_STORAGE`+`CAMERA` permissions to take photo from camera and save it to gallery
Followings  are GPS permission and  how to apply for Google Map API KEY.
```xml
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
```
![image](1.png)

# Know bugs
```
22/09/19 - Camera not working in API 29
```



