🖱️ AI Mouse – Gesture Controlled Virtual Mouse

Control your computer using hand gestures powered by MediaPipe, OpenCV, and PyAutoGUI.
This project turns your webcam into an AI-powered controller for mouse actions, volume control, scrolling, and more.

✨ Features
🎯 Right Hand Gestures

Cursor Movement → Move mouse pointer with index finger.

Left Click → Fold index finger while keeping thumb apart.

Right Click → Fold middle finger gesture.

Double Click → Fold both index + middle fingers together.

Screenshot → Thumb + index pinch gesture (saved as PNG).

✋ Left Hand Gestures

Scroll Up / Down → Open palm + thumb up/down.

Volume Control → Thumb–index pinch to adjust volume, mute below threshold.

📊 Visual Feedback

On-screen gesture labels.

Mute icon when volume muted.

Volume bar with percentage.

🛠️ Tech Stack

Python 3.x

OpenCV
 – Image processing

MediaPipe
 – Hand landmark detection

PyAutoGUI
 – Mouse & keyboard automation

Pynput
 – Mouse control

PyCaw
 – System audio control

🚀 Setup & Usage

1️⃣ Clone the repo
git clone https://github.com/your-username/AI-Mouse.git
cd AI-Mouse

2️⃣ Install dependencies
pip install opencv-python mediapipe pyautogui pynput pycaw comtypes numpy

3️⃣ Run the script
python ai_mouse.py

4️⃣ Controls

Use Right Hand for mouse, click, double-click, screenshot.

Use Left Hand for scroll and volume control.

Press q to exit.
