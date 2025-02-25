
# Face Detection Website 🎭

A Face Detection Website using face-api.js that can detect faces, facial landmarks, expressions, age, and gender in real-time using a webcam.

## 📌 Description

This project is a simple web application built using HTML, CSS, and JavaScript with the face-api.js library to detect facial features. The website allows users to access their webcam and provides real-time analysis of their face.

## 🛠️ Technologies Used

- HTML - Structure of the webpage.

- CSS - Styling for UI enhancements.

- JavaScript - Main logic to interact with face-api.js.

- face-api.js - Library for facial recognition and analysis.

## ✨ Features

✔️ Real-time Face Detection

✔️ Facial Landmarks Detection

✔️ Expression Recognition (Happy, Sad, Angry, etc.)

✔️ Age Estimation

✔️ Gender Classification

✔️ Webcam Integration
## 🤖API Reference

#### Face Detection API and Models form-

```http
  https://github.com/justadudewhohacks/face-api.js
```

#### Models Path Configuration
Ensure that modals are correctly loaded in ```script.js ```

```http
  Promise.all([
  faceapi.nets.tinyFaceDetector.loadFromUri("/models"),
  faceapi.nets.faceLandmark68Net.loadFromUri("/models"),
  faceapi.nets.faceRecognitionNet.loadFromUri("/models"),
  faceapi.nets.faceExpressionNet.loadFromUri("/models"),
  faceapi.nets.ageGenderNet.loadFromUri("/models"),
]).then(webCam);
```


👨‍💻 Developed with ❤️ using face-api.js 🤖.
