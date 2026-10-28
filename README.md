# StudentHub Android App

StudentHub is a beginner-friendly Android Application Development assignment built with **Java and XML layouts**.

## Features
- Splash screen with app name/logo and navigation to Login.
- Login with email/password validation and a local demo account.
- Registration with name, email, password, and confirm-password validation.
- Simulated forgot-password and reset-password flow.
- Dashboard with a `GridLayout` of module cards and icons.
- Profile screen showing the current user's name and email.
- Logout returns to Login.
- Explicit Intents connect Activities.
- `LinearLayout`, `GridLayout`, and `ConstraintLayout` are demonstrated.
- Default resources and night-mode colors are provided through `strings.xml`, `colors.xml`, and `values-night/colors.xml`.

## Demo Login
- Email: `student@example.com`
- Password: `123456`

You can also register a demo user in the app. Data is stored locally using `SharedPreferences`.

## Navigation Flow
Splash -> Login
- Login -> Dashboard (after successful login)
- Login -> Register -> Login
- Login -> Forgot Password -> Reset Password -> Login
- Dashboard -> Profile -> Logout -> Login

## How to Run
1. Install Android Studio and allow the Android SDK setup to finish.
2. Extract this project ZIP to a normal folder, for example `Documents/StudentHub_Android_Assignment`.
3. Open Android Studio.
4. Select **Open** and choose the extracted `StudentHub_Android_Assignment` folder, the one containing `settings.gradle`.
5. Allow Gradle sync and any required SDK downloads to finish.
6. If Android Studio asks to install missing SDK/build components, accept the recommended installation.
7. Create or select an Android emulator, or connect an Android phone with USB debugging enabled.
8. Press the green **Run** button.

## Notes
- This project is a classroom demonstration, not production authentication.
- Passwords are stored locally in SharedPreferences for demonstration only. Do not use this approach for a real app.
- Password recovery is simulated. No real recovery email is sent.
- Module cards other than Profile show demo Toast messages.
- The project uses Android Gradle Plugin 8.6.1 and compile SDK 35. Android Studio may download compatible build components on first sync.
