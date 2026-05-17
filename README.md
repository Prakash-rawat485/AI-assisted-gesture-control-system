# 🖐️ Dual-Hand Gesture Control System

An interactive computer vision application that allows you to control your computer's **system volume** and **screen brightness** using hand gestures in real-time. 

Built using **Python**, **OpenCV**, and **Google MediaPipe**, this system reads video data from your webcam, detects your hands, and updates system levels smoothly based on the distance between your thumb and index finger.

---

## 🚀 Key Features

*   **Dual-Hand Isolation**: Automatically tells your hands apart. 
    *   **Left Hand** 🔊 Controls Windows System Volume.
    *   **Right Hand** ☀️ Controls Laptop Screen Brightness.
*   **Signal Smoothing**: Employs an exponential moving average filtering pipeline to remove shaking and keep adjustments fluid.
*   **Intelligent Dead-Zone Mechanics**: Ignores microscopic hand tremors (`< 5 pixels`) to prevent flickering UI metrics.
*   **On-Screen Display (HUD)**: Draws active tracking lines and reveals dynamic real-time percentage gauges directly over your hands.

---

## 🛠️ Tech Stack & Dependencies

*   **Python 3.8+**
*   **OpenCV**: For camera access, video manipulation, and HUD rendering.
*   **MediaPipe (Tasks Vision)**: Google's lightweight machine learning framework used to detect 21 unique hand coordinates.
*   **PyCaw (Python Core Audio Windows Library)**: Direct low-level access to the Windows endpoint speaker driver utilities.
*   **NumPy**: Hand-landmark coordinate interpolation maps.

---
AUTHOR-

prakash rawat(data scientist)
