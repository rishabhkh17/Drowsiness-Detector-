# 😴 Drowsiness Detector

A real-time drowsiness detection system using OpenCV, Dlib, and Scipy. This project detects drowsiness by monitoring eye aspect ratio (EAR) and triggers an alarm when the user shows signs of falling asleep — making it ideal for drivers, heavy machinery operators, or anyone in need of alertness monitoring.

## 🚀 Features

- Detects human faces and eyes using dlib’s 68 facial landmarks
- Calculates Eye Aspect Ratio (EAR) in real time
- Sounds an alarm when drowsiness is detected
- Lightweight and easy to set up
- Cross-platform (Windows/Linux/macOS)

## 🛠️ How It Works

The detector uses the **Eye Aspect Ratio (EAR)** method:
- When your eyes are open, the EAR remains relatively constant.
- When you start closing your eyes, the EAR decreases significantly.
- If EAR drops below a threshold for a number of consecutive frames, the system triggers an alarm.

![Demo](https://github.com/rishabhkh17/Drowsiness-Detector-/blob/master/demo.gif)

## 📦 Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
