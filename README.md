# AgroTrack

🌾 **AgroTrack Project – Smart Crop Management System**

AgroTrack is a digital farming assistant designed to help farmers and agricultural managers efficiently track crop-related activities and receive timely reminders for essential farming tasks.

## Features

- 🎬 **Splash Screen** - Beautiful animated introduction
- 🔐 **Login System** - Secure authentication (default: admin/admin)
- 🏠 **Home Screen** - Google Pay-inspired design with image slider
- ⏰ **Add Reminder** - Set farming reminders with notifications
- 🚪 **Logout** - Secure session management

## Getting Started

This is a Flutter application built for agricultural management.

### Prerequisites

- Flutter SDK
- Android Studio (for Android development)
- Xcode (for iOS development)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/saurabhshinde4327/AgroTrack.git
```

2. Navigate to the project directory:
```bash
cd AgroTrack
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Default Login Credentials

- **Username:** admin
- **Password:** admin

## Building APK

To build an APK for Android:

```bash
flutter build apk --release
```

The APK will be generated in `build/app/outputs/flutter-apk/`

## Technologies Used

- **Flutter** - Cross-platform mobile development
- **Dart** - Programming language
- **Material Design 3** - UI/UX design system
- **SharedPreferences** - Local data storage
- **Flutter Local Notifications** - Reminder notifications
- **Intl** - Internationalization support

## Project Structure

```
lib/
├── main.dart
└── screens/
    ├── splash_screen.dart
    ├── login_screen.dart
    ├── home_screen.dart
    └── add_reminder_screen.dart
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For support, please open an issue in the GitHub repository.

---

**Built with ❤️ for the agricultural community**