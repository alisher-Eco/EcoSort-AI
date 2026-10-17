# EcoSort AI 

Smart Computer Vision & AI-Powered Waste Classification System.

##  About the Project
**EcoSort AI** is an engineering project designed to solve the problem of waste sorting using modern technologies. Instead of manual sorting, this system uses computer vision to detect objects in real-time, classify them into appropriate categories (Recyclable, Paper, General Waste), and prepare data for automated hardware sorting.

## Tech Stack
- **Language:** Python 3
- **Computer Vision:** OpenCV (`cv2`)
- **AI / Object Detection:** YOLOv8 (Ultralytics)
- **Environment:** IDLE / VS Code

## Features
- Real-time video stream processing via web-camera.
- Automatic object detection and bounding box visualization.
- Smart categorization into:
  - **PLASTIC / GLASS / METAL** (Green)
  - **PAPER / CARDBOARD** (Yellow)
  - **GENERAL WASTE** (Red)
- Console logging for tracking and hardware integration.

## How to Run
1. Install required libraries:
   ```bash
   pip install opencv-python ultralytics

