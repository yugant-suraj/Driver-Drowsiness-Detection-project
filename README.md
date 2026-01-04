# 🚘 Driver Drowsiness Detection (Computer Vision)

> Real-time driver drowsiness detection using facial landmark analysis and eye aspect ratio (EAR).

---

## Overview
This project implements a **real-time computer vision pipeline** to detect driver drowsiness from a live video stream. It continuously monitors eye activity and raises alerts when prolonged eye closure is detected, helping reduce fatigue-related accidents.

The system is optimized for **low latency**, **CPU-only execution**, and **real-world deployment scenarios**.

---

## System Design

---

## Key Features
- Real-time face and eye detection
- Eye Aspect Ratio (EAR)–based fatigue inference
- Temporal smoothing to reduce false positives
- Audio / visual alerting
- CPU-only execution (no GPU required)

---

## Tech Stack
- Python
- OpenCV
- Dlib
- NumPy
- imutils
- SciPy

---

## Performance Notes
- Detects sustained eye closure within seconds
- Runs smoothly on CPU
- Works reliably under normal lighting conditions

---

## Limitations
- Sensitive to poor lighting
- Reduced accuracy with extreme head pose
- Not optimized for night-time infrared feeds

---

## Future Work
- CNN-based eye state classification
- Yawn detection integration
- Embedded deployment (Raspberry Pi / Jetson)
- Mobile inference optimization

---

## Repository Structure

---

## Setup
```bash
pip install opencv-python dlib imutils numpy scipy
jupyter notebook Drowsiness_detector.ipynb

