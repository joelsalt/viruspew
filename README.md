#Setup
1. Install node
2. run `npm install`
3. run `npm install serve -g`
4. run `npm install cordova -g`
5. install android sdk
6. install java jdk
6. run `cordova create <folder name>`
7. run `cordova add platform browser`
8. run `cordova add platform android`

#Running the Application

###In chrome
1. open up a terminal and cd to the top level project directory.
2. run `serve` and navigate to the shown link.

###In App Webview
1. cd to the top directory
2. run `cordova run browser`

###Build Android APK
1. cd to the top directory.
2. run `cordova run android`
3. look for android-debug.apk in 'platforms\android\build\outputs\apk'.
4. Turn on developer mode in the android device : Navigate to 'About Device' in Settings and tap 'Build Number'7 times.
5. Go to 'Lock Screen and Security' and turn on 'Unknown Sources'.
6. Put the .apk on your device and install it.
