# Face Emotion Recognition Android App

This Android application uses a pre-trained Keras model converted to TensorFlow Lite (TFLite) to detect faces in images and assign emotions to them.

## Features

- Detects faces in images.
- Assigns one of the following emotions to each detected face: Happy, Sad, Angry, Neutral, Surprise, Fear, Disgust.
- Uses a pre-trained Keras model for emotion recognition, converted to TFLite for mobile use.

## Requirements

- Android Studio
- Android device or emulator with Android API level 21 (Lollipop) or higher

## Setup

1. Clone this repository to your local machine.
2. Open the project in Android Studio.
3. Run the app on your Android device or emulator.

## Usage

1. Open the app.
2. Select an image from your device or take a new photo.
3. The app will process the image, detect faces, and assign emotions to them.
4. The processed image with assigned emotions will be displayed as text with other details.

## Model

The emotion recognition is powered by a pre-trained Keras model based on expNet architecture that has been converted to TFLite for use on mobile devices.

## Disclaimer
This app is intended for educational purposes only.
