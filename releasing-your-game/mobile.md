# Mobile

## Requirements

* [Node.js](https://nodejs.org/en/)

## Installing Apache Cordova

```text
$ npm install -g cordova
```

## Creating your project

```text
$ cordova create MyGame
```

Running this command will make Cordova create all the directories and files it needs to run. When it's over, copy all the files of your monogatari game to the `www` directory Cordova created.

## Building your App for Android

```text
$ cordova build android --prod --release
```

### Distribution via APK files

### Distribution on the Play Store

Distributing your game in the play store requires you to become a developer with a one-time payment.

## Building your App for iOS

```text
$ cordova build iOS --prod --release
```

