# AI-HSV-Color-Tracking-with-OpenCV


This project provides a real-time object tracking system using HSV color filtering and OpenCV. It is optimized to run inside a **Jupyter Notebook (e.g., VS Code)** and allows dynamic HSV calibration via OpenCV trackbars.

---

## 🖼️ Features

- 📷 Real-time webcam video feed.
- 🎨 Dynamic HSV color range adjustment via OpenCV trackbars.
- 🟡 Object detection with colored bounding circles.
- ⚫ White-mask preview of detected objects.
- 🎚️ Adjustable thresholds for precise color tuning.
- 🧪 Works inside Jupyter Notebooks and Python scripts.

---

## 📦 Requirements

Install the required Python libraries:
pip install opencv-python imutils numpy
### 🚀 How to Run
Open the Jupyter Notebook or VS Code.

Copy the full code into a Jupyter cell.

Run the cell.

## Three OpenCV windows will appear:

Trackbars → Adjust HSV range

Tracking → Webcam feed with detected objects

Mask → White region showing matched object

## 🛑 To stop:
Press the q key in any OpenCV window.
### 🎯 Example HSV Settings for Red
You can set these in the trackbars to detect red-colored objects:

Lower HSV: H: 0, S: 100, V: 100

Upper HSV: H: 13, S: 255, V: 255
### 🧠 Example Output

Yellow circle shows object, red dot is center


White area is the detected object in mask view


