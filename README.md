 # chat_app

A new Flutter project.
💬 Flutter Chat App
👩‍💻 Developer: “I built a real-time chat app with Flutter + Firebase.”
🤔 Reviewer: “Oh really? What can it do?”
👩‍💻 Developer:
..Show when users are online / offline / typing ✅
..Send and receive messages instantly ✅
..Update ticks: single → double (sent → delivered) ✅
..Run on two devices at the same time ✅
🚀 Getting Started
👩‍💻 Developer:
“To run it on your machine, just follow me step by step.”
✅ 1. Clone the Repository
  Run in your terminal:git clone https://github.com/HARIKAMADIREDDY/chat_app.git
✅ 2. Navigate into the Project Folder
  cd chat_app
✅ 3. Install Dependencies
   flutter pub get
🔑 Firebase Setup
🤔 Reviewer: “But how does it connect to Firebase?”
👩‍💻 Developer:
“Good question! You’ll need to configure Firebase first.”
1.Install FlutterFire CLI
 dart pub global activate flutterfire_cli
2.Run configuration
 flutterfire configure
3. automatically adds config files into your project:
Android → android/app/google-services.json
lib -> lib/firebase_options.dart
for windows(https://youtu.be/gptBM2CPMQs?si=FEpZ4PE0XqBFltjR)
4.In Firebase Console, enable:
->Authentication (Google or Email/Password)
->For google signin want to add sha1 and sha256 keys then again redownload google-services.json
->Firestore Database
->Realtime Database
📸 Demo Showcase
👩‍💻 Developer:
“Here’s what the app looks like in action.”
<img width="1680" height="1050" alt="Image" src="https://github.com/user-attachments/assets/4aa5ce3c-e52d-4322-953a-8d12f2f34d8c" />
<img width="1680" height="1050" alt="Image" src="https://github.com/user-attachments/assets/6d88e8bf-ab77-430e-974e-eb68ec6c429b" />
<img width="1680" height="1050" alt="Image" src="https://github.com/user-attachments/assets/10911f35-bdf8-4ed9-bd3a-1e50aee497b4" />
<img width="1680" height="1050" alt="Image" src="https://github.com/user-attachments/assets/1cef7a30-0eee-454b-a24f-9a47f4abc19a" />
✅ Features
Real-time chat with Firebase Firestore
User presence via Realtime Database
Delivery ticks like WhatsApp
Works on Android, iOS, Web
💡 How to Run on Two Devices
flutter run -d emulator-5554   # first emulator
flutter run -d emulator-5556   # second emulator
# or: one emulator + chrome
👩‍💻 Developer:
“That’s it! Clone, set up Firebase, and chat away 🚀”
🤔 Reviewer:
“Beautifully done. Clean, professional, and fun to read.”
