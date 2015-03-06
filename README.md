android-support-v4-preferencefragment
=====================================

Unofficial PreferenceFragment compatibility layer for Android 1.6 and up. Includes resources so add this as a library project to your project.

## Usage

1. Clone the library project

    ```
    $ git clone https://github.com/kolavar/android-support-v4-preferencefragment.git
    ```

2. Deploy aar library into local maven

    ```
    $ cd android-support-v4-preferencefragment
    $ ./gradlew uploadArchives
    ```
    Now, aar should be within your local maven repository. eg: ~/.m2/repository/com/android/support/support-v4-preferencefragment/1.0.0

3. Reference it in the application project

    Add compile 'com.android.support:support-v4-preferencefragment:1.0.0' within the dependencies block of your app's build.grade.
    If there is no mavenLocal() within your repositories block, add it too.
