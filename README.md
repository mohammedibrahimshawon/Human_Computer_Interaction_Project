# 🖐️ Controlling Mouse Cursor Using Hand Gesture

A real-time system to control the Windows mouse cursor using static and dynamic hand gestures, enhancing Human-Computer Interaction (HCI) without the need for direct physical input devices.

---

## 👨‍💻 Authors
- Mohammed Ibrahim Shawon  
- Md. Tahsinur Rahman  
- Mahreen Tabassum  
- Nusrat Jahan Ekra  

---

## 🎯 Abstract
This project presents a gesture-controlled virtual mouse that utilizes a webcam to recognize human hand gestures and control mouse operations (movement and clicks) in real time. The system requires no external devices and relies on computer vision and machine learning techniques for gesture detection.

---

## 🧠 System Architecture

![System Architecture Diagram](https://github.com/mohammedibrahimshawon/Human_Computer_Interaction_Project/raw/master/1hci.png)

- Captures real-time video feed using a built-in or external webcam.
- Detects and classifies hand gestures using **MediaPipe** and computer vision algorithms.
- Translates recognized gestures into mouse events:
  - Cursor movement
  - Left click
  - Right click
  - Double click

> Hand position and recognized gestures control mouse events. Colored markers or specific hand postures improve tracking accuracy.

---

## 📚 Background and Motivation

Hand gestures provide a natural form of communication. Traditional input devices like mice and keyboards can be limiting in certain contexts. This system eliminates the need for physical contact, enabling applications in assistive technology, cleanrooms, medical environments, and smart interfaces.

Inspired by advances in machine learning and computer vision, this project leverages low-cost hardware to create intuitive interaction methods.

---

## 🛠️ Technologies & Libraries Used

- Python 3.x  
- OpenCV  
- MediaPipe (Google)  
- PyAutoGUI  
- NumPy  
- pyttsx3 (text-to-speech, optional)  
- SpeechRecognition (optional voice commands)  
- pybind11 (C++ binding for performance)  

---

## 📊 Evaluation

![Gesture Recognition Interface](https://github.com/mohammedibrahimshawon/Human_Computer_Interaction_Project/raw/master/hvi2.png)

- Real-time hand tracking and gesture recognition with high accuracy.  
- Supports both **bare hand gestures** and **color glove-based detection**.  
- Integrates voice commands to extend interaction capabilities.  
- Runs smoothly on Windows platforms with standard webcams.  
- Improved user experience under different lighting conditions.

---

## ✅ Features

- Mouse cursor movement using hand position.  
- Left click, right click, and double click recognition via gestures.  
- Voice command support (optional).  
- No additional hardware required beyond a webcam.  
- Two modes for gesture detection:  
  - Bare hand (MediaPipe)  
  - Color glove detection for precision.

---

## 🧪 Getting Started

### Prerequisites

- Python 3.x installed on Windows  
- Webcam connected or built-in

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammedibrahimshawon/Human_Computer_Interaction_Project.git
   cd Human_Computer_Interaction_Project

2. Install required Python packages:

bash
Copy
Edit
pip install -r requirements.txt

3 .Running the Application
bash
Copy
Edit
python gesture_mouse_control.py

####  How to Use
Position your hand in front of the webcam.

Move your hand to control the mouse cursor.

Use specific hand gestures to perform left click, right click, or double click.

Optionally, use voice commands if enabled.

📖 References
https://www.sciencedirect.com/science/article/pii/S2351978918304438

https://www.sciencedirect.com/science/article/pii/S2212017316001389

Bankar RT, Salankar SS. Head gesture recognition system using gesture cam, Fifth International Conference on Communication Systems and Network Technologies, 2015.

📝 License
This project is intended for educational and research purposes. Please contact the authors for collaboration or commercial use.

🧾 Authors' Note
This project leverages state-of-the-art machine learning and computer vision techniques to improve user interaction with computers by using natural hand gestures, making technology more accessible and intuitive.
