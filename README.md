# 🚗 Gesture Controlled Car Game

Control a car game using your hand gestures instead of a keyboard!  
This project uses **Computer Vision**, **OpenCV**, and **MediaPipe** to detect hand movements in real-time and control the car inside the game.

---

# 📌 Project Overview

Gesture Controlled Car Game is an AI-powered computer vision project where users can play a racing/car game using only hand gestures captured through a webcam.

The system tracks hand movements and converts them into game controls such as:

- ⬅️ Move Left
- ➡️ Move Right
- ⏸️ Stop / Pause
- 🚀 Accelerate

This project combines:

- Python
- OpenCV
- MediaPipe
- Hand Tracking
- Game Control Automation

to create an interactive touchless gaming experience.

---

# 🎮 Features

## ✋ Real-Time Hand Tracking
- Detects hand landmarks using webcam feed
- Tracks finger and palm movements

## 🎯 Gesture-Based Controls
- Control the car using gestures
- No keyboard required

## ⚡ Fast Response
- Real-time gesture recognition with low latency

## 🧠 Computer Vision Integration
- Uses AI-based hand landmark detection

## 🖥️ Interactive Gameplay
- Makes gaming more immersive and fun

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main Programming Language |
| OpenCV | Video Processing |
| MediaPipe | Hand Tracking |
| NumPy | Array Operations |
| PyAutoGUI / Keyboard | Game Controls |
| Webcam | Gesture Input |

---

# 📂 Project Structure

```bash
Gesture-Controlled-Car-Game/
│
├── main.py               # Main application file
├── camera.py             # Webcam and hand tracking
├── requirements.txt      # Required libraries
├── assets/               # Images / game assets
├── output/               # Output screenshots/videos
├── model/                # Gesture models (if available)
└── README.md
