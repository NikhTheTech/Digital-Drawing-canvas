# 🎨 Hands-free Digital Drawing Canvas

A **hands-free, webcam-based drawing canvas** built with **Python**, **OpenCV**, and **MediaPipe**.
Draw on a digital canvas using **hand gestures** — no mouse, no touchscreen. Just wave your hand, select colors, and start creating!

---

## 📌 Features

* **Hands-Free Drawing:** Draw on the canvas using hand gestures without needing a mouse, stylus, or touchscreen.
* **Multiple Colors:** Choose from **Blue, Green, Red, and Yellow** to create vibrant, colorful drawings.
* **Clear Functionality:** Easily reset the canvas with the **CLEAR** button to start fresh anytime.

---

## ⚙️ Installation

Clone the repository and install dependencies:

```
git clone https://github.com/NikhTheTech/Digital-Drawing-canvas.git
cd Digital-Drawing-canvas

pip install opencv-python mediapipe numpy
```

---

## 🚀 Usage

Run the main script:

```
python hands_free_drawing.py
```
---

## 🚀 Usage

1. **Launch the application:** Run the Python script:

```
python hands_free_drawing.py
```

2. **Position yourself:** Sit or stand in front of your webcam so your hand is fully visible.
3. **Draw:** Move your **index finger** to draw lines on the canvas.
4. **Switch Colors:** Move your finger to the top menu to select **Blue, Green, Red, or Yellow**.
5. **Clear Canvas:** Move your finger to the **CLEAR** box to reset the canvas.
6. **Stop Drawing:** Close your thumb near your index finger to end a stroke.
7. **Quit:** Press `q` to exit the application.

---

## 📂 Project Structure

```
Hands-free-Digital-Drawing-Canvas/
│
├── hands_free_drawing.py     # Main program
├── README.md                 # Project documentation
└── requirements.txt          # (Optional) Dependencies list
```

---

## 🛠️ Tech Stack

* **Python 3.x**
* **OpenCV** – image processing & drawing
* **MediaPipe** – hand tracking & gesture detection
* **NumPy** – efficient array operations

---

## 🧠 How It Works

1. **Webcam Feed:** Captures frames from your webcam
2. **Hand Tracking:** Detects landmarks using MediaPipe Hands
3. **Index Finger Tracking:** Uses fingertip position as a virtual pen
4. **Drawing:** Draws lines on both live frame & blank canvas
5. **Gesture Controls:** Detects button areas (CLEAR / COLORS) based on fingertip position

---

## 📌 Future Improvements

* ✨ Add support for more colors and thickness control
* 🖌️ Add eraser tool
* 📁 Save drawings as image files
* 🎥 Improve gesture recognition with additional hand poses

