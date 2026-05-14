# Real-Time Object Detection and Tracking with YOLOv8 🚀

This repository contains my submission for **Task 4** of my AI Internship. The project demonstrates a real-time computer vision system that detects and tracks multiple objects simultaneously.

##  Project Overview
The core objective of this project is to implement an intelligent tracking system. Unlike simple detection, this system assigns a unique, persistent ID to each object, allowing the AI to "remember" and follow specific objects as they move across the frame.

##  Key Features
- **Object Tracking:** Uses the **BoT-SORT** algorithm to maintain unique IDs for every object.
- **Real-time Detection:** High-speed processing of webcam frames.
- **Visual Feedback:** Displays bounding boxes, class labels, and tracking IDs in real-time.
- **Wide Coverage:** Detects 80+ categories including persons, laptops, phones, and more.

##  Tech Stack
- **AI Model:** YOLOv8 (Ultralytics)
- **Language:** Python
- **Libraries:** OpenCV, NumPy
- **Environment:** Google Colab / Local Python

##  Project Structure
- `main.py`: Python script for local execution.
- `Object_Tracking.ipynb`: Interactive notebook for Google Colab.
- `README.md`: Project documentation.

##  How to Run
1. Install requirements:
   ```bash
   pip install ultralytics opencv-python
