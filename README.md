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

1.`Tools >Firebase` in Android Studio

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
1. 開啟Android studio 點選`Google Maps Activity project`
<img src="https://github.com/shen2255678/-/blob/master/1.png" width="300" alt="day"/>
2.After the project is created, you will see a file google_maps_api.xml with a link to apply for a Google Maps API key. Copy the link and go to the application key
<img src="https://github.com/shen2255678/-/blob/master/3.png" width="500" alt="day"/>
3.
<img src="https://github.com/shen2255678/-/blob/master/4.png" width="300" alt="day"/>
4.
<img src="https://github.com/shen2255678/-/blob/master/5.png" width="375" alt="day"/>
5.Paste the key into google_maps_key in AndroidManifest.xml
<img src="https://github.com/shen2255678/-/blob/master/6.jpg" width="450" alt="day"/>

# Know bugs
```
22/09/19 - Camera not working in API 29
```



