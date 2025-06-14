# Haptic Navigator and Visual Information Scanner

> A smart assistive device that enables visually impaired individuals to navigate complex environments and
> access visual information through haptic feedback and AI-based recognition.

[ View Full Project on Hackster.io](https://www.hackster.io/DSAY_Diablo27/haptic-navigator-and-visual-information-scanner-c87b81)
 Overview

This project combines depth sensing, haptic feedback, and embedded AI to create a real-time assistance system for the visually impaired.
It features obstacle detection and avoidance, currency and product recognition, and OCR-based text reading — all integrated into a wearable prototype.

---

## 💡 Key Features

- **Real-time Path Planning** using monocular depth estimation and A* algorithm.
- **Haptic Feedback Navigation** to guide users through unfamiliar surroundings.
- **Text Recognition & Reading** with OCR, enabling printed text access.
- **Object and Currency Detection** using TinyML models trained on custom datasets.
- **Embedded System Implementation** using STM32 and servo-controlled feedback.

---

## 🛠 Tech Stack
## 🛠️ Hardware Stack

| Component | Description |
|----------|-------------|
| **UNIHIKER SBC** | IoT Python-based single board computer with touchscreen |
| **Raspberry Pi 5** | Core AI inference engine and vision processing |
| **XIAO ESP32S3 Sense** | TinyML-based classification and secondary processing |
| **STM32F411 BlackPill** | Real-time control for haptic feedback and motors |
| **Grove Ultrasonic Sensors (x5)** | Distance measurement and obstacle mapping |
| **Logitech HD Webcams (x3)** | Depth estimation, OCR, and object recognition |
| **Vibrating Disc Motor** | Tactile feedback for navigation alerts |
| **Speaker (0.25W, 8Ω)** | Audio output for TTS and alert messages |

---

## 💻 Software & Frameworks
- **OpenCV** for image processing
- **Tesseract OCR** for text recognition
- **Edge AI models** (Monocular Depth + Classification)
- **MicroPython / C** on microcontrollers
- **Python + Flask** for interfacing
- **Path Planning** using A* algorithm

---

---

For full project steps, architecture, and code walkthrough,
visit the [Hackster.io page](https://www.hackster.io/DSAY_Diablo27/haptic-navigator-and-visual-information-scanner-c87b81).

---
