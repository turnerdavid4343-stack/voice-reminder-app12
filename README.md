# Voice Reminder (Compose) - Minimal Template

This is a minimal Android project skeleton (Jetpack Compose, Kotlin) implementing a two-screen UI similar to the image you provided:
- Home screen with a large "Add task by voice" button, a task card, and a bottom bar
- Time picker screen with hour/minute columns and a Set button

Notes:
- This is a template for demonstration and GitHub upload. It does not include full voice-to-text logic or persistent storage.
- To run: open in Android Studio 2023.3+ with the Android SDK installed. You may need to adjust Gradle/AGP versions for your environment.


## Added features
- Voice-to-text using RecognizerIntent
- Local DB using Room (Task entity, DAO, Database)
- Simple notification via AlarmManager and BroadcastReceiver

Run in Android Studio: build and install on a device (Speech intent requires device/emulator with Google app).