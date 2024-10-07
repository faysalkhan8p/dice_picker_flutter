# Dice Picker Flutter

A simple Flutter application where two users can interact with two dice displayed on the screen. Each player can roll the dice by tapping on them, generating random dice values for interactive fun. This project is ideal for learning Flutter basics like handling gestures, state management, and user interface updates.

## Features
- Two dice displayed on the screen, one for each player.
- Tapping on a dice rolls it, generating a random number between 1 and 6.
- Each player can tap their dice to interact independently.

## Getting Started

### Prerequisites

Before building and running the app, ensure you have the following installed:

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/) with Flutter and Dart extensions
- Android or iOS simulator/emulator, or a physical device for testing

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/dice_picker_flutter.git
    ```

2. Navigate to the project directory:

    ```bash
    cd dice_picker_flutter
    ```

3. Install Flutter dependencies:

    ```bash
    flutter pub get
    ```

### Running the App

1. Connect an Android/iOS device or start an emulator/simulator.

2. Run the app using the following command:

    ```bash
    flutter run
    ```

Alternatively, you can use Android Studio or VS Code to launch the app:

- **Android Studio**: Open the project, and click the green "Run" button.
- **VS Code**: Open the project, press `F5` or select **Run > Start Debugging**.

### How to Use

- When the app starts, two dice are displayed on the screen, one for each user.
- Tap on the dice to roll it. The dice will display a random number between 1 and 6.
- Each user can roll their respective dice by tapping on it.

## Building for Release

To build the app for release on Android or iOS, follow these steps:

### Android

1. Run the following command to build the APK:

    ```bash
    flutter build apk --release
    ```

2. The APK will be generated in the `build/app/outputs/flutter-apk/` directory.

### iOS

1. Ensure you have Xcode installed on macOS.

2. Run the following command to build the iOS app:

    ```bash
    flutter build ios --release
    ```

3. Follow the instructions in the terminal to complete the iOS build process.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Please follow the [contributing guidelines](CONTRIBUTING.md) when submitting code changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Happy coding!
