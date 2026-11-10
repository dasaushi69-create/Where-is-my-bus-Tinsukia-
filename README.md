# Where Is My Bus? — Tinsukia (starter prototype)

This is a Flutter Android starter app for a local-bus information service.

## What works in this prototype
- Home screen with origin/destination selection
- Search interaction
- Sample timetable screen
- Live tracking placeholder with an honest GPS-not-connected status
- Ticket-booking placeholder

## Important
All route names, stops and times in `lib/main.dart` are demo placeholders. They are NOT verified Tinsukia bus routes or schedules. Do not publish them as real service information.

Live GPS requires:
1. A driver app or approved GPS device on each participating bus.
2. Explicit permission from bus operators and drivers.
3. A backend (for example Firebase) to receive and share location updates.
4. A map provider and a valid API key.
5. A privacy policy, location-permission explanation and secure access rules.

Ticket booking requires operator agreements, confirmed seat inventory, fare rules and a payment provider. Keep booking disabled until those are in place.

## Run it
1. Install Flutter SDK and Android Studio.
2. Unzip this project.
3. Open a terminal in this folder and run:
   - `flutter pub get`
   - `flutter run`
4. To build an Android APK:
   - `flutter build apk --release`
5. APK output: `build/app/outputs/flutter-apk/app-release.apk`

This starter contains only Flutter SDK dependencies. Create the Android platform folder if needed with `flutter create .` from this project directory.
