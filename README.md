# NUVYARA — See Beyond What Happened

**NUVYARA** is an interactive Android TV / Amazon Fire TV-compatible prototype that helps users explore cause and effect, understand outcomes, and imagine alternative possibilities.

## About the Project

NUVYARA turns outcomes into an interactive journey. Users navigate event cards with a TV remote, explore why an event happened, understand its consequences, and consider what might happen if a different choice were made.

## Features

- Interactive event cards designed for a TV screen
- Cause-and-effect explanations
- A **What If** experience for exploring alternative outcomes
- Remote-friendly navigation
- AWS-powered reflection retrieved through an API

## AWS Integration

NUVYARA connects to AWS Lambda through Amazon API Gateway. The Android application sends a request to the reflection endpoint and displays the returned message.

**Endpoint:**  
https://zar1at2jj6.execute-api.ap-southeast-2.amazonaws.com/NUVYARA/reflection

## Technology Stack

- Java
- Android Studio
- Android TV emulator
- AWS Lambda
- Amazon API Gateway

## How to Test

1. Open the project in Android Studio.
2. Allow Gradle sync to complete.
3. Run the app on an Android TV emulator or compatible device.
4. Use the remote directional controls to navigate the event cards.
5. Select an event to explore its explanation and alternative possibilities.
6. Verify the AWS reflection using the endpoint above.

## Project Status

NUVYARA is a working prototype. Further improvements may include more dynamic reflections, enhanced error handling, and additional interactive scenarios.

## Vision

Every outcome has a cause, every consequence offers a lesson, and every alternative opens a possibility.

**NUVYARA — See beyond what happened.**
