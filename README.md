# WebsiteAsApp 
Turn your websites into a native android app within a few minutes, with splash screen support and even more! 

## Overview

The WebsiteAsApp Android Template allows you to quickly convert a website into a native Android application. Users only need to edit a simple configuration file to specify the website URL, written in simple java. The application features a splash screen with loading ability at startup. Feel free to directly implement or modify even further!

## Getting Started

Follow these steps to integrate the template into your Android Studio project:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/SharafatKarim/WebsiteAsApp
   ```

2. **Open in Android Studio:**

   Open Android Studio and select "Open an existing Android Studio project." Navigate to the cloned repository and select the `WebsiteAsApp` directory.

3. **Edit Configuration:**

   Open the `app/src/main/res/values/strings.xml` file and modify the `website_url` string to the URL of the website you want to convert.

   ```xml
   <resources>
       <string name="app_name">WebsiteAsApp</string>
       <string name="website_url">https://www.example.com/</string>
   </resources>
   ```

6. **Change App Icon:**

   Users can change the app icon by replacing the existing icon files located in the app/src/main/res directory. Feel free to simple replace or append!
  > TIP: There are several online generators to automate this process of generating android app icons.

5. **Customize Splash Screen:**

   The application features a splash screen with loading ability. Customize the splash screen by modifying the layout and styles in `res/layout/activity_splash.xml` and `res/values/styles.xml`.

6. **Build and Run:**

   Build and run the application on an Android emulator or a physical device.

## Features

- Converts a website into a native Android app.
- Supports JavaScript and DOM storage.
- Implements a WebView for seamless website integration.
- Splash screen with loading ability at startup.
- Provides a customizable UI with a progress bar and loading screen.

## Customization

Feel free to customize the template according to your requirements. You can modify the UI, add features, or tweak the WebView settings. The splash screen layout and styles can be adjusted in the `res/layout/activity_splash.xml` and `res/values/styles.xml` files. Feel free to extend.

## Extending the Project

This project can serve as a base model and can be extended further with additional features or improvements. Consider contributing to the project by [creating an issue](https://github.com/SharafatKarim/WebsiteAsApp/issues) or submitting a pull request.

## Contributing

If you encounter any issues or have suggestions for improvements, please [create an issue](https://github.com/SharafatKarim/WebsiteAsApp/issues) or submit a pull request.

## License

This template is licensed under the [MIT License](LICENSE).
