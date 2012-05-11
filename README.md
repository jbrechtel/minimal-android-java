minimal-android-java
====================

This is a demonstration of the minimal files and ceremony needed to build an Android application.  Only 4 files are used for building.

    MainActivity.java
    pom.xml
    icon.png
    AndroidManifest.xml

You must have the [Android SDK](http://developer.android.com/sdk/index.html) installed and your ANDROID_HOME environment variable set.
You also need Maven.

To build the project run:

    mvn package
   
To install the build package to an attached device or running emulator run:

    adb install -r target/helloworld.apk