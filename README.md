# Real-Time Object Detection with OpenCV and SSD MobileNet

This project demonstrates real-time object detection using OpenCV and a pre-trained SSD MobileNet model, capturing video from a webcam and highlighting detected objects with bounding boxes and labels.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- SSD MobileNet v3 Large Coco model (2020_01_14): `frozen_inference_graph.pb` and `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`
- A `things.names` file with class names listed one per line.

## Setup

1. **Python & OpenCV:** Ensure Python 3.x and OpenCV are installed.
2. **Model Files:** Download `frozen_inference_graph.pb` and `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`.
3. **Class Names:** Create a `things.names` file with the object class names.

## Running the Detector

1. Place the model files and `things.names` in your project directory.
2. Run the script: `python your_script_name.py`. Ensure your webcam is connected.

## Code Overview

The script sets up the webcam, loads the class names, initializes the detection model with the SSD MobileNet configuration and weights, and processes frames in a loop to detect and annotate objects with bounding boxes and class labels.

## Customization

Modify the confidence threshold, input size, or other parameters in the script for different detection needs.

## Acknowledgments

- OpenCV Library
- TensorFlow Object Detection API

