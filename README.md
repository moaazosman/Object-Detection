# Object Detection with MobileNetSSD Model

This repository contains a Python script for real-time object detection using the MobileNetSSD (Single Shot MultiBox Detector) model. The script captures video from the webcam and detects objects in the frames in real-time. It utilizes the OpenCV library for image and video processing, and the imutils library for efficient frame resizing and FPS calculation.

## Features

- Real-time object detection using the MobileNetSSD model.
- Adjustable confidence threshold for object detection.
- Bounding box visualization with class labels.
- Efficient frame processing and display using imutils and OpenCV.
- Clean and easily understandable code structure.

## Requirements

- Python 3.x
- OpenCV (cv2) library
- imutils library
- Webcam (for real-time video capture)

## Usage

1. Clone the repository to your local machine.
2. Make sure you have Python and the required libraries installed.
3. Run the `object_detection.py` script using a Python interpreter.
4. The script will access your webcam and display real-time object detection results.

## Configuration

You can modify the following parameters in the `object_detection.py` script:

- `confidence_level`: Set the confidence threshold for object detection.
- `vs = cv2.VideoCapture(0)`: Change the argument to access a different video source (e.g., a video file).

## Acknowledgments

This project is based on the MobileNetSSD model and utilizes the OpenCV and imutils libraries. Credits to the respective authors and contributors of these projects.


Feel free to use and modify the code according to your needs. If you find this project helpful or have suggestions for improvements, feel free to contribute or create issues.
