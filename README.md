# 🚦 Traffic Object Detection Using YOLOv8 & OpenCV

## Project Overview

This project demonstrates real-time object detection in traffic surveillance videos using the YOLOv8 (You Only Look Once) deep learning model. The system processes traffic footage and identifies various road objects such as vehicles, pedestrians, motorcycles, buses, and trucks with high accuracy.

The primary objective is to leverage computer vision techniques to automate traffic monitoring and provide insights for intelligent transportation systems.

---

## Problem Statement

Manual traffic monitoring is time-consuming and inefficient, especially in high-density urban environments. This project aims to develop an automated object detection system capable of detecting and tracking traffic participants in video streams using state-of-the-art deep learning models.

---

## Dataset

**Input Source:** `Traffic.mp4`

The project uses a traffic video containing multiple road users and moving vehicles. The video is processed frame-by-frame to detect and visualize objects in real time.

---

## Project Workflow

1. Load Traffic Video
2. Load Pre-trained YOLOv8 Model
3. Read Video Frames
4. Perform Object Detection
5. Draw Bounding Boxes and Labels
6. Display Detection Results
7. Process Video Until Completion

---

## Model Used

### YOLOv8 (You Only Look Once)

Two YOLOv8 variants were explored:

* **YOLOv8n (Nano)** – Lightweight and optimized for faster inference.
* **YOLOv8x (Extra Large)** – Higher accuracy model for improved detection performance.

The project also supports GPU acceleration using CUDA for faster processing and real-time inference.

---

## Features

* 🚗 Vehicle Detection
* 🏍️ Motorcycle Detection
* 🚌 Bus Detection
* 🚚 Truck Detection
* 🚶 Pedestrian Detection
* 🎥 Real-Time Video Processing
* ⚡ GPU Acceleration with CUDA
* 📦 Bounding Box Visualization
* 🧠 Deep Learning-Based Object Detection

---

## Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* PyTorch
* CUDA (GPU Acceleration)
* Jupyter Notebook

---

## Project Structure

```text
├── Object Detection in Traffic.ipynb   # Main Notebook
├── Traffic.mp4                         # Input Traffic Video
└── README.md                           # Project Documentation
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/traffic-object-detection.git
cd traffic-object-detection
```

### Install Dependencies

```bash
pip install ultralytics opencv-python torch
```

---

## How to Run

1. Place the traffic video (`Traffic.mp4`) in the project directory.
2. Open the Jupyter Notebook.
3. Run all notebook cells.
4. The model will process the video and display detected objects with bounding boxes and class labels.

---

## Applications

* Smart Traffic Management
* Intelligent Transportation Systems (ITS)
* Traffic Flow Analysis
* Vehicle Monitoring
* Road Safety Analytics
* Urban Planning

---

## Results

The YOLOv8 model successfully detects and classifies multiple objects in traffic scenes in real time. The implementation demonstrates the effectiveness of deep learning-based object detection for automated traffic surveillance and monitoring applications.

---

## Future Improvements

* Implement Multi-Object Tracking (MOT)
* Vehicle Counting System
* Speed Estimation
* Traffic Density Analysis
* Lane Detection Integration
* Real-Time Camera Stream Support
* Custom Model Training on Traffic Datasets

---

## Conclusion

This project showcases the power of YOLOv8 and computer vision for real-time traffic object detection. By combining deep learning with video processing techniques, the system provides an efficient and scalable solution for traffic monitoring and intelligent transportation applications.

---

## Author

Developed as a Computer Vision and Deep Learning project using YOLOv8 for real-time traffic object detection and analysis.
