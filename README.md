# Digital Camera Calibration - Practical AI Fundamentals

This project focuses on calibrating digital cameras to assess and correct various sensor imperfections. This is a crucial step in many fields, including industrial inspection, satellite remote sensing, and astronomy, where precise image data is essential.

## Project Overview

This repository provides a practical approach to camera calibration, including gray level analysis, noise reduction, and pixel defect correction. It covers essential image processing tasks using Python and OpenCV.

### Learning Objectives

* Conduct basic image processing operations.
* Gain practical experience with camera sensors.
* Understand common sources of sensor errors.
* Learn basic correction methods for image sensor errors.

## Key Tasks

### 1. Grayscale Wedge Capture and Analysis

* Capture a grayscale wedge to evaluate the camera’s ability to reproduce known brightness levels.
* Extract and analyze individual gray levels to calculate mean and standard deviation for each step.
* Use OpenCV for image capture, conversion, and analysis.

### 2. Dark Frame Capture

* Capture 10 dark frames to measure pixel-level noise and offset.
* Calculate an average dark frame to reduce readout noise and eliminate offset.
* Use this dark frame for correcting subsequent images.

### 3. White Frame Capture

* Capture 10 flat-field (white) images to assess pixel sensitivity variations and vignetting.
* Use this to normalize pixel responses and improve overall image consistency.

### 4. Pixel Defect Detection and Correction

* Detect and correct dead, stuck, and hot pixels using the dark and white frames.
* Interpolate defective pixels to enhance image quality.

## Technical Requirements

* Python (3.8+ recommended)
* OpenCV (cv2)
* Jupyter Notebook

## Instructions

* Maintain fixed camera exposure settings throughout the experiment.
* Store all images in lossless PNG format to preserve quality.
* Include all code and analysis in a Jupyter notebook.

## Repository Structure

📁 Camera_Calibration_Project
│
├── 📂 images
│   ├── grayscale_wedge.png
│   ├── dark_frame_average.png
│   └── white_frame_average.png
│
├── 📂 notebooks
│   └── Camera_Calibration.ipynb
│
└── README.md
```

## License

This project is released under the MIT License.
