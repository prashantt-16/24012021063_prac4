# MAD Practical 4 – Implicit and Explicit Intents

## Aim
To develop an Android application that demonstrates the use of **implicit and explicit intents** to perform common actions and navigate between activities.

## Introduction
An **Intent** is a messaging object used by Android components to request an action from another component.

- **Implicit Intent:** Requests an action without naming a specific component. Android finds an app that can handle the action.
- **Explicit Intent:** Names the component that should be opened, such as another activity in the same application.

## Practical Tasks
The application demonstrates intent-based actions such as:

- Opening a website using a URL.
- Opening the phone dialer for a specified phone number.
- Opening the call log.
- Opening the image gallery.
- Opening the camera.
- Setting an alarm.
- Navigating to a Login Activity using an explicit intent.

> The exact actions available depend on the implementation and the apps installed on the Android device or emulator.

## Concepts Used
- `Intent`
- `Intent.setData()`
- `Intent.setType()`
- `startActivity()`
- `Uri.parse()`
- `ActivityResultContracts` (where required)
- Android manifest declarations and runtime permissions (where required)

## Technologies Used
- Android Studio
- Kotlin
- XML for user interface layouts
- Android SDK

## How to Run
1. Clone or download this repository:
   ```bash
   git clone https://github.com/prashantt-16/24012021063_prac4.git
   ```
2. Open the project in Android Studio.
3. Allow Gradle sync to complete.
4. Start an Android emulator or connect an Android device with USB debugging enabled.
5. Click **Run** to build and launch the application.
6. Test the available buttons and grant permissions if Android requests them.

## Expected Outcome
The application demonstrates how Android intents can launch supported system apps or activities and how an explicit intent can navigate from one activity to another.

## Learning Outcome
After completing this practical, the student understands the difference between implicit and explicit intents and how to use intents to open system features and navigate between activities.

## Repository
[24012021063_prac4](https://github.com/prashantt-16/24012021063_prac4)
