# setup-app-icon

A document to remember how to properly setup a IOS/Android App Icon.

It's possible to generate the android icon directly in Android Studio or you can use a site to generate as https://appicon.co.

## Android

Here you have two options:

1. Generate the app icons in the Android Studio by clicking in the res folder with the right click then selecting New > Image Asset. (Android Studio itself will replace all icons)
2. Replace the ic_launcher.png and ic_launcher_round.png images in each mipmap-\* in the path /android/app/src/main/res accordly with their sizes.

Done!

## IOS

- Open the project folder in Xcode then click on the folder named "Images.xcassets".
- Drag and drop the icon with the required dimension.

Done!
