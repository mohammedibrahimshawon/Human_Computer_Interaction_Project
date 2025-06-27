# 🖐️ Controlling Mouse Cursor Using Hand Gesture

A real-time system to control the Windows mouse cursor using static and dynamic hand gestures, enhancing Human-Computer Interaction (HCI) without the need for direct physical input devices.

## 👨‍💻 Authors
- Mohammed Ibrahim Shawon  
- Md. Tahsinur Rahman  
- Mahreen Tabassum  
- Nusrat Jahan Ekra  

## 🎯 Abstract
This project presents a gesture-controlled virtual mouse that utilizes a webcam to recognize human hand gestures and control mouse operations (movement and clicks) in real time. The system requires no external devices and relies on computer vision and machine learning techniques for gesture detection.

## 🧠 System Architecture
- The system captures real-time video feed using a built-in or external webcam.
- Using **MediaPipe** and **Computer Vision algorithms**, it detects and classifies hand gestures.
- Recognized gestures are translated into mouse events:
  - Cursor movement
  - Left click
  - Right click
  - Double click

> The hand position and recognized gesture control the corresponding mouse event. Colored markers or specific hand postures are used for better gesture tracking.

## 📚 Background and Motivation
Hand gestures are a natural form of human interaction. Traditional input devices like a mouse or keyboard can be limiting in certain use cases. This system aims to eliminate physical contact, especially useful in:
- Assistive technologies
- Smart environments
- Cleanroom and medical interfaces

Inspired by advances in machine learning, image processing, and low-cost hardware availability, the project showcases the power of intuitive interaction.

## 🛠️ Technologies & Libraries Used
- Python
- OpenCV
- MediaPipe (by Google)
- PyAutoGUI (for cursor control)
- NumPy
- pybind11 (C++ binding)
- Compatible with **Windows OS**

## 📊 Evaluation
- Real-time hand tracking and gesture recognition.
- Supports both **bare hand gestures** and **colored glove inputs**.
- High accuracy and responsiveness with minimal hardware requirements.
- Integrates **voice command support** for extended interaction (e.g., opening apps, system control).

## ✅ Features
- Cursor movement via hand tracking
- Left, Right, Double click detection
- Voice command integration
- No additional hardware required
- Works in various lighting conditions
- Two gesture detection modes:
  - Bare hand (MediaPipe)
  - Color-glove mode for enhanced precision

## 🧪 How to Run
1. Clone the repository.
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
