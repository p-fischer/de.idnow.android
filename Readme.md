How to use the .aar file:
--------------------

Copy the sdk-release.aar into the apps libs folder.

In your app.gradle add:
repositories {
    flatDir {
        dirs 'libs' //this way we can find the .aar file in libs folder
    }
}

and in the dependencies part of your app.gradle add:

    compile 'com.example.library:sdk-release@aar' (replace the 'com.example.library' with your packagename)



Additional dependencies to add in your app.gradle
--------------------

    compile 'com.google.code.gson:gson:2.2.4'
    compile 'org.atmosphere:wasync:2.1.2'
    compile 'org.slf4j:slf4j-android:1.7.12'
    compile 'com.squareup.retrofit:retrofit:1.9.0'
    compile 'com.fasterxml.jackson.core:jackson-core:2.6.0-rc3'
    compile 'com.fasterxml.jackson.core:jackson-annotations:2.6.0-rc3'
    compile 'com.fasterxml.jackson.core:jackson-databind:2.6.0-rc3'
	


