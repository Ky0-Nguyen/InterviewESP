# ESP application

An Application for interview at ESP Media company

<img src="https://github.com/thienthanmeo/InterviewESP/blob/master/ImageApplication/1.png" width="200" height="400"/>
<img src="https://github.com/thienthanmeo/InterviewESP/blob/master/ImageApplication/2.png" width="200" height="400"/>
<img src="https://github.com/thienthanmeo/InterviewESP/blob/master/ImageApplication/3.png" width="200" height="400"/>
<img src="https://github.com/thienthanmeo/InterviewESP/blob/master/ImageApplication/4.png" width="200" height="400"/>
<img src="https://github.com/thienthanmeo/InterviewESP/blob/master/ImageApplication/5.png" width="200" height="400"/>

## Enviroment

```
- XCode
- Android Studio
- Command Line Tools

* Installing dependencies
You will need Node, Watchman, the React Native command line interface, and Xcode.

While you can use any editor of your choice to develop your app, you will need to install Xcode in order to set up the necessary tooling to build your React Native app for iOS.

Node, Watchman
We recommend installing Node and Watchman using Homebrew. Run the following commands in a Terminal after installing Homebrew:

- brew install node
- brew install watchman

If you have already installed Node on your system, make sure it is Node 8.3 or newer.

Watchman is a tool by Facebook for watching changes in the filesystem. It is highly recommended you install it for better performance.

* The React Native CLI

Node comes with npm, which lets you install the React Native command line interface.

Run the following command in a Terminal:

- npm install -g react-native-cli

If you get an error like Cannot find module 'npmlog', try installing npm directly: curl -0 -L https://npmjs.org/install.sh | sudo sh.


```


## Installation in application

```
npm install -> install all module in application
react-native link -> link module in native app (xcode, anroid studio)

```

## Run on Simulator or Emulator

```

npm start -> start sever of react-native
react-native run-ios -> run application with platform is IOS on simulator
react-native run-android -> run application with platform is ANDROID on emulator

```

## Running On Device

- https://facebook.github.io/react-native/docs/running-on-device
 


## Build application

npm start -> start sever of react-native
IOS: build with xcode 
ANDROID:  build with Android Studio or command code 

## Generating the release APK
Simply run the following in a terminal:

```
$ cd android
$ ./gradlew assembleRelease
```

```
Note: Make sure gradle.properties does not include org.gradle.configureondemand=true as that will make the release build skip bundling JS and assets into the APK.
```

Gradle's assembleRelease will bundle all the JavaScript needed to run your app into the APK. If you need to change the way the JavaScript bundle and/or drawable resources are bundled (e.g. if you changed the default file/folder names or the general structure of the project), have a look at android/app/build.gradle to see how you can update it to reflect these changes.

The generated APK can be found under android/app/build/outputs/apk/release/app-release.apk, and is ready to be distributed.
