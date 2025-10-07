# -Hand-Gesture-Controlled-Volume-System-using-Computer-Vision
# Hand Gesture Controlled Volume System

This project is an interactive system that allows users to **control their computer’s audio volume using hand gestures** detected through a webcam. It uses **Computer Vision** techniques and **Python** libraries to interpret hand movements and map them to volume control levels.

---

## 🎯 Project Goals

* Implement a touch-free method to control system volume.
* Utilize hand gesture recognition for real-time interaction.
* Demonstrate the use of **OpenCV** and **MediaPipe** in computer vision applications.

---

## ⚙️ Features

* Detects and tracks hand landmarks in real-time.
* Adjusts system volume based on distance between fingers.
* Smooth and responsive gesture-to-action mapping.
* Simple and user-friendly interface.

---

## 🧰 Technologies Used

* **Python**
* **OpenCV** (for video capture and image processing)
* **MediaPipe** (for hand tracking and gesture detection)
* **PyCaw** (for controlling system audio on Windows)

---

## 🚀 How It Works

1. The webcam captures a live video feed.
2. MediaPipe detects and tracks hand landmarks.
3. The distance between the thumb and index finger is calculated.
4. This distance is mapped to the system’s volume range.
5. The program continuously updates the volume as gestures change.

---

## 🪜 Steps to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Ashish-Kumar3059/-Hand-Gesture-Controlled-Volume-System-using-Computer-Vision
   ```
2. Navigate to the project folder:

   ```bash
   cd hand-gesture-volume
   ```
3. Install dependencies:

   ```bash
   pip install opencv-python mediapipe pycaw
   ```
4. Run the program:

   ```bash
   python hand-gesture_volume.py
   ```

---


## 📚 Future Enhancements

* Add gesture-based mute/unmute feature.
* Extend to brightness or media control.
* Support multiple gesture types and recognition modes.

---

## 👨‍💻 Author

**Ashish Kumar**
*IT Student | Data Analyst Enthusiast | Tech Innovator*

GitHub: https://github.com/Ashish-Kumar3059

---

