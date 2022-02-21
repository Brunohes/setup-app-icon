# setup-app-icon

A document to remember how to properly setup a IOS/Android App Icon.

It's possible to generate the android icon directly in Android Studio or you can use a site to generate as https://appicon.co.

## Android

- Open the folder in path /android/app/src/main/res
- There, you will find folders starting with mipmap-\*
- Replace the ic_launcher.png and ic_launcher_round.png images in each mipmap-\* folder accordly with their sizes.
- Verify in AndroidManifest.xml if the names are the same.
- Done!

## IOS

- Open the project folder in Xcode then click on the folder named "Images.xcassets".
- Drag and drop the icon with the required dimension.
- Done!
