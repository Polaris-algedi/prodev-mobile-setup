# React Native Development Setup with Expo Go

## Objective

Mobile development requires more computational resources compared to web development. To simplify the development and testing process, we are using the Expo Framework for React Native. This allows us to efficiently develop and test mobile applications.

## Prerequisites

Before proceeding, ensure you have the following installed:

- **Node.js LTS** (Latest Long-Term Support version)
- **VS Code** (Recommended IDE)
- **macOS, Linux, or Windows**
- **Expo Go** installed on your physical device (Android or iOS)

These tools are essential for a smooth development experience.

## Why Expo Go?

Mobile development often requires using emulators to test applications. However, maintaining updated emulators for multiple devices (e.g., iPhone 7 to iPhone 16 Pro Max, various Android models) can be resource-intensive and costly.

Expo Go provides a lightweight and cost-effective solution by allowing you to test and run React Native applications directly on your physical device. It supports both iOS and Android without the need for complex configurations.

## Steps to Install Expo Go

1. Visit the official [Expo Go homepage](https://expo.dev/go).
2. Select the latest SDK version.
3. Click on the appropriate installation link for your device:
   - **Android:** Install from the [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent).
   - **iOS:** Install from the [Apple App Store](https://apps.apple.com/app/expo-go/id982107779).
4. Open the Expo Go app on your device.
5. Create a new account or log in if you already have one.

## Challenges Faced

During the setup process, I encountered issues connecting my phone using Expo Go. I received a "Failed to connect" error. To resolve this, I downloaded Android Studio and installed the Expo APK for simulators. After setting up the emulator, I was able to successfully connect and run my application.
