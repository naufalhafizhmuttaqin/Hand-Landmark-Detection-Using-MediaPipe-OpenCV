# Hand Landmark Detection Using MediaPipe & OpenCV

This project demonstrates real-time **hand landmark detection** using a webcam with **MediaPipe Hands** and **OpenCV**.  
It detects hands and visualizes the 21 hand landmarks along with their connections.

## 🚀 Features
- Real-time hand detection from webcam
- Visualizes **21 hand landmarks**
- Supports multiple hands
- Mirrored camera view for intuitive interaction
- Lightweight and easy to run

## 🧠 How It Works
MediaPipe Hands detects hands and returns **21 landmarks** per hand.  
Each landmark represents a key joint or fingertip on the hand.  
The detected landmarks are drawn on the video stream using OpenCV.

## 🛠️ Technologies Used
- Python
- OpenCV
- MediaPipe

## 📦 Requirements
Install the required libraries using pip:

```bash
pip install opencv-python mediapipe
