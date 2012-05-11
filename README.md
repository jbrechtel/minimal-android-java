minimal-android-java
====================

Minimal Android Project in Java

You must have the [Android SDK](http://developer.android.com/sdk/index.html) installed and your ANDROID_HOME environment variable set.

To build the project run:

    mvn package
   
To install the build package to an attached device or running emulator run:

    adb install -r target/helloworld.apk