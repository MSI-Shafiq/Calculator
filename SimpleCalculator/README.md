<h1 align="center">Simple Calculator App</h1> 

<p align="center">
I created a simple and easy to use calculator app for Android smart phones. I made this project in Android Studio and coded it with Java. My main purpose of this project was to practice getting used to the new Android Studio enviornment as there have been several updates to it since I've last downloaded it. 
</p>

<p align="center">
A link to an APK file for Android users can be found here: <a href="https://github.com/aahmad4/Simple-Calculator/blob/master/app-debug%5B1%5D.apk" target="_blank">app-debug[1].apk</a>
</p>

## Repository Contents
* [MainActivity.java](https://github.com/aahmad4/Simple-Calculator/blob/master/app/src/main/java/com/example/calculator/MainActivity.java) contains all the logic for my program including object-orientated programming, conditional statement use, functions, as well as try catch statements. 
* [layout/activity_main.xml](https://github.com/aahmad4/Simple-Calculator/blob/master/app/src/main/res/layout/activity_main.xml) contains all the xml design code for my portrait mode of the app.
* [layout-land/activity_main.xml](https://github.com/aahmad4/Simple-Calculator/blob/master/app/src/main/res/layout-land/activity_main.xml) contains all the xml design code for the landscape version of my app. 

## App Platform

![](ss1.png) ![](bp1.png)

![](screenshot.png)
![](bp2.png)

## Setup

#### Clone
```
git clone https://github.com/aahmad4/Simple-Calculator
```
#### Usage
```
cd Simple-Calculator
```
Initiate a debug APK build:
```
gradlew assembleDebug
```
Build APK and immediately install on running emulator or connected device:
```
gradlew installDebug
```
Mac or Linux Prefix:
```
./gradlew task-name
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
