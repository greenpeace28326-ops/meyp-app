# Middle East Yellow Pages - Android App

WebView app for http://middleeastyellowpages.com

## Get the APK (no coding tools needed)
1. Create a free account at github.com and make a new repository.
2. Upload ALL files/folders from this project (keep the `.github` folder).
3. Open the Actions tab > "Build APK" > wait ~3 min for the green tick.
4. Open the run > Artifacts > download `MiddleEastYellowPages-apk` (zip) > extract `app-debug.apk`.
5. Send the APK to your phone, open it, allow "Install unknown apps", install.

## Or with Android Studio
File > Open this folder > Build > Build APK(s).
Output: app/build/outputs/apk/debug/app-debug.apk

## Change site URL / name
- URL: HOME_URL and HOST in MainActivity.java
- Name: app/src/main/res/values/strings.xml
