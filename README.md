# Mood-detection
# Facial Emotion Recognition 🎭 | OpenCV + DeepFace

Real-time facial emotion detection using [OpenCV](https://opencv.org/) and [DeepFace](https://github.com/serengil/deepface). This lightweight application captures video from a webcam, detects faces, and predicts the associated emotion using pre-trained deep learning models. Emotion labels are displayed live on the video feed.

![Demo Screenshot](https://github.com/manish-9245/Facial-Emotion-Recognition-using-OpenCV-and-Deepface/assets/69393822/57c41270-7575-4bc7-ae7a-99d67239a5ab)

---

## 🚀 Features
- 🔍 Real-time face detection using Haar cascades
- 🧠 Emotion recognition using DeepFace (pre-trained models)
- 🎯 Minimal and efficient codebase
- 📷 Live webcam feed with emotion overlay

---

## 📦 Requirements

Install dependencies via pip:
pip install -r requirements.txt

## 🛠 Setup Instructions
1. Clone the Repository
   
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

2. Download Haar Cascade
   
haarcascade_frontalface_default.xml
Place it in the project directory (if not already present).

3. Run the App

python emotion.py

## 🧠 How It Works
Load Haar cascade for face detection.

Capture frames from webcam.

Convert to grayscale for face detection.

Convert detected faces to RGB format.

Use DeepFace to analyze emotions on detected faces.

Display detected emotions on the video stream.

## 📄 License

This project is licensed under the terms of the MIT License.

## 🌟 Acknowledgements

Made by Shaurya Agrawal
