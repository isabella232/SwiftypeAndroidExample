# SwiftypeAndroidExample

This example app shows how easy it is to get started with [SwiftypeAndroid](https://github.com/swiftype/SwiftypeAndroid) to add [Swiftype-powered search](https://swiftype.com) to your Android application.

To run the sample application:

1. Check out the code.
2. Check out the SwiftypeAndroid git submodule.

    git submodule init
    git submodule update

3. Start the Android Studio and open the SwiftypeAndroidExample/SwiftypeAndroidExample project. Add `SwiftypeAndroidExample/SwiftypeAndroid` as a module. You should now be able to compile the project.
4. Edit the `SwiftypeAndroidExample/res/values/swiftype_config.xml` file to add your engine key (you can find this on your Swiftype dashboard). You must also change the `search_content_provider_authority` to add a unique identifier for your application, or it will conflict with other users of the SwiftypeAndroid library.
5. Click the Run button to launch the emulator.

Don't have a crawler-based [or WordPress] search engine yet? Go to [swiftype.com](https://swiftype.com), sign up if you haven't yet, and create a new engine.

## License

This code is MIT licensed. See LICENSE.txt for details.
