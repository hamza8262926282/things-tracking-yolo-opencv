# 🎯 Real-Time Object Tracking with YOLO and OpenCV

This project demonstrates real-time object detection and tracking using the **YOLOv3** model with **OpenCV**, implemented in Python via a Jupyter Notebook. It focuses on tracking only selected classes for performance and relevance.

---

## 🧠 Tracked Object Categories

This implementation detects and tracks the following 6 object types:

- 🧍 Person  
- 🚗 Car  
- 🏍️ Motorcycle  
- 🐕 Dog  
- 🍾 Bottle  
- 🪑 Chair  

These classes are filtered from the full YOLO COCO dataset for focused detection and efficiency.

---

## 📁 Files Included

- `Things tracking with YOLO and OPen Cv.ipynb` — Main Jupyter Notebook containing full code and logic for object tracking.

---

## ⚙️ How It Works

1. **YOLOv3** runs object detection on each frame of a video stream.
2. **OpenCV** is used for reading video input, drawing bounding boxes, and displaying output.
3. The notebook filters detected objects to track only 6 specific classes listed above.

---

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install opencv-python numpy
