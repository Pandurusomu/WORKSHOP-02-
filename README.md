# WORKSHOP-02-
Perform real-time object detection using a trained YOLO v4 model through your laptop camera

# 🧠 Real-Time Object Detection using YOLOv4

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Enabled-green.svg)](https://opencv.org/)
[![YOLOv4](https://img.shields.io/badge/YOLOv4-Object%20Detection-red.svg)](https://github.com/AlexeyAB/darknet)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Perform **real-time object detection** using a **trained YOLOv4 model** through your **laptop camera**.  
This project demonstrates how to combine **OpenCV** with **YOLOv4** for fast and accurate object detection on live video streams.

---

## 🚀 Features
- 🎥 Detect multiple objects in **real-time** from your laptop camera
- ⚡ Built using **YOLOv4** (high speed & accuracy)
- 🧠 Works with **pre-trained** or **custom-trained** YOLO models
- 🖼️ Draws bounding boxes, class labels, and confidence scores
- 💻 Lightweight — runs locally on CPU or GPU

---

## 🧰 Tech Stack
- **Python 3.7+**
- **OpenCV** (for camera & visualization)
- **YOLOv4** (object detection backbone)
- **NumPy** (matrix operations)

---

## 📦 Installation

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/yolov4-realtime-object-detection.git
cd yolov4-realtime-object-detection
pip install -r requirements.txt
pip install opencv-python numpy

yolov4-realtime-object-detection/
│
├── yolo-coco/                  
│   ├── yolov4.cfg              # Model configuration
│   ├── yolov4.weights          # Pre-trained weights
│   └── coco.names              # Object class names
│
├── main.py                     # Main detection script
├── requirements.txt            # Dependencies list
└── README.md                   # Project documentation


python main.py

[ Laptop Camera Feed ]
→ Person (93%)
→ Laptop (88%)
→ Bottle (76%)

```

