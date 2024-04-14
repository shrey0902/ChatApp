Chat App README
Welcome to our Chat App! This Flutter app allows users to sign up, upload profile images, send and receive messages, and receive push notifications using Firebase.

Features
Sign-Up: Users can create a new account by providing their email, username, and password.
Profile Picture Upload: Users can upload a profile picture during the sign-up process or later in their profile settings.
Messaging: Users can send text messages to other users in real-time.
Push Notifications: Users receive push notifications for new messages when the app is not actively in use.


Technologies Used
Flutter: Dart language for frontend development.
Firebase: For user authentication, image storage, real-time database for messaging, and push notifications.
JavaScript: Used for Firebase Cloud Messaging (FCM) configuration and handling push notifications.


Getting Started
Clone the repository: git clone https://github.com/your-repo-url.git
Open the Flutter project in your preferred editor (e.g., Visual Studio Code, Android Studio).
Install Flutter dependencies: flutter pub get
Set up Firebase:
Create a new Firebase project on the Firebase Console.
Add your Android/iOS app to the Firebase project and follow the setup instructions to download the google-services.json (for Android) or GoogleService-Info.plist (for iOS) files and place them in the appropriate directories in your Flutter project.
Enable Firebase Authentication, Firebase Cloud Messaging (FCM), and Firebase Realtime Database in your Firebase project console.
Update Firebase configurations:
Update android/app/build.gradle and ios/Runner/Info.plist with your Firebase configurations.

Run the app:
Connect a device or start an emulator.
Run flutter run in the terminal to launch the app on the device/emulator.
Contributing
We welcome contributions to improve the app. Please fork the repository, make your changes, and submit a pull request for review.
