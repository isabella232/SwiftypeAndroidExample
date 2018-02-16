# Swiftype Android Example App for Swiftype Site Search

This example app shows how easy it is to get started with [SwiftypeAndroid](https://github.com/swiftype/SwiftypeAndroid) to add [Swiftype-powered Site Search](https://swiftype.com) to your Android application.

> **Note:** This client has been developed for [Swiftype's Site Search](https://www.swiftype.com/site-search) API endpoints only. You may refer to the [Swiftype Site Search API Documentation](https://swiftype.com/documentation/site-search/overview) for additional context.

To run the sample application:

1. Check out the code.
2. Check out the SwiftypeAndroid git submodule.

    git submodule init
    git submodule update

3. Start the Android Studio and open the SwiftypeAndroidExample/SwiftypeAndroidExample project.
4. Add `SwiftypeAndroidExample/SwiftypeAndroid` as a module.
5. Go to File -> Project Structure. Click SwiftypeAndroid -> Dependencies. Select "Export" on all Android Support libraries and apply the new settings. You should now be able to compile the project.
6. Edit the `SwiftypeAndroidExample/res/values/swiftype_config.xml` file:
    1. Set your Engine Key in the `engine_key` parameter
    2. Update the `search_content_provider_authority` to be unique for your application.
    3. Set the document_types parameter value to @array/crawler_based if using a crawler-based engine or @array/wordpress if using a WordPress plugin-based engine.

    NOTE: If you make changes to the `swiftype_config.xml` file after the first run, make sure to increment the `database_version`.

7. Click the Run button to launch the emulator.

Don't have a crawler-based or WordPress-based search engine yet? Go to [swiftype.com](https://swiftype.com), sign up if you haven't yet, and create a new engine.

## License

This code is MIT licensed. See LICENSE.txt for details.
