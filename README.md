
---

# 🔍 Object Detection Suite

A comprehensive collection of Python scripts leveraging **OpenCV** to perform various object detection tasks. This repository serves as a modular toolkit for learning and implementing computer vision pipelines, ranging from static image analysis to real-time webcam streams.

## ⚡ Getting Started

### Prerequisites

Ensure you have Python installed, then install the required dependencies:

```bash
pip install opencv-python numpy

```

### Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/SithilSemitha/objectdetection.git
cd objectdetection

```

### Running a Module

Execute any script using Python. For example, to start real-time detection:

```bash
python t2.py

```

---

## 📌 Script Directory

This project is organized into modular scripts, each focusing on a specific aspect of the detection pipeline:

| Script | Feature | Description |
| --- | --- | --- |
| **t1.py** | **Static Detection** | Processes local image files and identifies objects. |
| **t2.py** | **Live Stream** | Accesses the default webcam for real-time inference. |
| **t3.py** | **Video Processing** | Runs the detection pipeline on pre-recorded `.mp4` or `.avi` files. |
| **t4.py** | **Visualization** | Focuses on drawing and styling bounding boxes (thickness, colors). |
| **t5.py** | **Threshold Logic** | Implements confidence filtering to reduce "ghost" detections. |
| **t6.py** | **Multi-Class** | Handles simultaneous detection of multiple different object categories. |
| **t7.py** | **UI Enhancements** | Adds polished labels, background contrast, and FPS counters. |
| **t8.py** | **Full Demo** | An integrated script combining all features into one robust pipeline. |

---

## 🛠 How It Works

The scripts typically follow a standard Computer Vision (CV) workflow:

1. **Input Acquisition:** Loading an image or capturing a frame from a video/webcam.
2. **Preprocessing:** Resizing and normalizing the frame for the model.
3. **Inference:** Passing the frame through a pre-trained model (e.g., SSD, YOLO, or Haar Cascades).
4. **Post-processing:** Applying **Non-Maximum Suppression (NMS)** and confidence thresholds.
5. **Rendering:** Overlaying bounding boxes and class labels onto the visual output.

---

## 📷 Sample Output

*(Replace the placeholders below with your actual images in the `assets/` folder)*

| Image Detection | Webcam Interface |
| --- | --- |
|  |  |

---

## 📘 Technologies Used

* **OpenCV:** The core library for image processing and the DNN module.
* **NumPy:** Used for high-performance matrix operations on image frames.
* **Pre-trained Models:** Supports integration with MobileNet-SSD, YOLO, and more.
---
