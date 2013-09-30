# Xamarin.Android.Suport.Binding #

## About ##

This project provides bindings for the latest revision of the `android-support-v7-appcompat.jar` library.

It is built against the latest version of the V4 support library which must be downloaded from the Xamarin component store.

Nuget packages are produced for both the V4 and V7-AppCompat libraries.

## Build instructions ##
 * Place Xamarin.Android.Support.v4-r18.dll into the `V4.Binding\lib\MonoAndroid` folder. It can be downloaded from the Xamarin component store.
 * Install the android support library component in the Android SDK manager. 
Set the `ANDROID_SDK_HOME` environment variable to the root of your Android SDK folder.
 * Build the android-support-v7-appcompat library in eclipse. ( See below )
 * Run psake.cmd

## Building the library in eclipse
 * In eclipse. File -> New -> Project
 * Android project from existing code
 * Select `ANDROID_SDK_HOME\extras\android\support\v7\appcompat`
 * Press finish. The project will build automatically
 * bin and res folders should have been created. 

## Links ##
* [Xamarin Store Android Support v4 (Rev18)](http://components.xamarin.com/view/xamandroidsupportv4-18/)
* [Android Support Library Doucmentation](http://developer.android.com/tools/support-library/index.html)