phonegap
========

phonegap examples

http://phonegap.com/

Doc:

http://docs.phonegap.com/

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
Run on an device using phonegap app (download from google play:https://play.google.com/store/apps/details?id=com.adobe.phonegap.app) and then:
```
$ phonegap serve
```
using the app connect to the server [IP]:3000
using the app instaled from ""

####Log:
```
$ adb logcat
```
####Debug:

https://developer.chrome.com/devtools/docs/remote-debugging
