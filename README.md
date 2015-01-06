phonegap
========

phonegap examples

http://phonegap.com/

Doc:

http://docs.phonegap.com/

##Install:

Java & Android: .bashrc path example:
```
#java & android
export JAVA_HOME=~/Documents/jdk1.8.0_25
export ANDROID_HOME=~/Documents/android-sdk-linux
export PATH=$PATH:$JAVA_HOME/bin:$ANDROID_HOME/tools
```
Ant:
```
$ sudo apt-get install ant
```

Nodejs:
```
$ sudo apt-get install nodejs npm
$ sudo ln -s /usr/bin/nodejs /usr/bin/node
```

Phonegap:
```
$ sudo npm install -g phonegap
```
Create App:
```
$ phonegap create myapp
$ phonegap run android
```
Run on an device:

```
$ adb devices
$ phonegap run android --device
```
