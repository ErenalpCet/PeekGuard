# PeekGuard - Privacy Protection App

PeekGuard is an Android application designed to protect your privacy by detecting when multiple faces are looking at your screen.

## Features
- **Real-time Face Detection**: Uses Google ML Kit to detect faces in the front-facing camera feed.
- **Privacy Alerts**: 
    - A semi-transparent red overlay appears on the screen when more than one face is detected.
    - A local notification is sent to warn the user: "Alert: Someone may be looking at your screen."
- **CameraX Integration**: High-performance camera implementation using modern Android APIs.
- **Lifecycle Aware**: Efficiently manages camera resources by stopping processing when the app is in the background.
- **On-Device Processing**: No image data leaves the device. All processing is done locally via ML Kit.

## Setup Instructions
1. Open the project in Android Studio (Giraffe or newer recommended).
2. Sync the project with Gradle files.
3. Run the app on a device with Android 10 (API 29) or higher.
4. Grant the CAMERA permission when prompted.
5. Use the "Enable Monitoring" toggle to start protection.

## Permission Rationale
- **CAMERA**: Required to access the front-facing camera for real-time face detection. The app does NOT record or save any photos or videos.

## Privacy Policy
PeekGuard processes all camera frames on-device. No images, videos, or facial data are stored, transmitted, or shared with any third-party services or servers.
