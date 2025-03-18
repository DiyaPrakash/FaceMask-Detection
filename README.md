# Face Mask Detection System

## Overview
This project implements a **real-time face mask detection system** using **deep learning and computer vision**. It detects whether a person is wearing a face mask or not and provides an alert if a mask is not detected.

## Features
- Detects faces using a **pre-trained Deep Learning model**.
- Classifies faces as **"With Mask" or "Without Mask"**.
- Uses **MobileNetV2** for accurate face mask detection.
- Issues an **audio alert** when a face without a mask is detected.
- Processes real-time video feed from a webcam.

## Technologies & Libraries Used
- **Deep Learning**: TensorFlow, Keras, MobileNetV2  
- **Computer Vision**: OpenCV, imutils  
- **Pre-trained Face Detection Model**: Caffe-based SSD (Single Shot MultiBox Detector)  
- **Audio Alert**: Playsound  
- **Data Augmentation**: ImageDataGenerator  

## Installation & Setup
### 1. Clone the Repository
```sh
git clone <repository-url>
cd <repository-folder>
```

### 2. Install Dependencies
```sh
pip install -r requirements.txt
```

### 3. Train the Mask Detection Model (Optional)
```sh
python Trainer.py
```

### 4. Run the Detection System
```sh
python Mask Detector.py
```

## Usage
- The system captures real-time video and detects if a face mask is present.
- If a person is **not wearing a mask**, an **audio alert** is played.
- The detected face is labeled with **"Face Mask Detected"** (Green) or **"No Face Mask Detected"** (Red).
- Press **'q'** to exit the application.

## License
This project is open-source and available under the **MIT License**.

