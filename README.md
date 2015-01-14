phonegap
========

phonegap examples

http://phonegap.com/

Doc:

http://docs.phonegap.com/

http://docs.phonegap.com/en/edge/cordova_camera_camera.md.html

##Install:

###Java & Android: .bashrc path example:
```
#java & android
export JAVA_HOME=~/Documents/jdk1.8.0_25
export ANDROID_HOME=~/Documents/android-sdk-linux
export PATH=$PATH:$JAVA_HOME/bin:$ANDROID_HOME/tools
```
###Ant:
```
$ sudo apt-get install ant
```

###Nodejs:
```
$ sudo apt-get install nodejs npm
$ sudo ln -s /usr/bin/nodejs /usr/bin/node
```

###Phonegap:
```
$ sudo npm install -g phonegap
```
####Create App:
```
$ phonegap create myapp
$ phonegap run android
```
####Run on an device:
```
$ adb devices
$ phonegap run android --device
```
Run on an device using phonegap app:

http://app.phonegap.com/

download from google play:https://play.google.com/store/apps/details?id=com.adobe.phonegap.app and then:
```
$ phonegap serve
```
using the app connect to the server [IP]:3000

####Log:
```
$ adb logcat
```
####Debug:

https://developer.chrome.com/devtools/docs/remote-debugging

http://stackoverflow.com/questions/21332853/is-there-a-real-solution-to-debug-cordova-apps

###Phonegap Interface design

http://onsen.io/

https://www.airpair.com/ionic-framework/posts/hybrid-apps-ionic-famous-f7-onsen
