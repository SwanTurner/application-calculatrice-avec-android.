# Calculator — Android Studio project

A native Android calculator with three modes:
- Standard
- Scientific
- Currency converter (live rates from Frankfurter API)

## Open the project
1. Extract `CalculatorAndroidStudio.zip`.
2. In Android Studio choose **Open**.
3. Select the extracted `CalculatorAndroidStudio` folder (the one containing `settings.gradle.kts`).
4. Let Gradle sync finish.
5. Select an emulator or Android phone and press **Run**.

## Requirements
- Android Studio with Android SDK installed
- JDK 17 (Android Studio's bundled JBR is recommended)
- Internet connection for the currency converter

The calculator modes work offline. Currency rates are retrieved from the Frankfurter public API when the converter is used. If the network is unavailable, the app displays an error instead of pretending the rate is current.
