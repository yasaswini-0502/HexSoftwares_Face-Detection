# HexSoftwares_Face-Detection
# Face Detection using OpenCV in Python
Demo video link : https://drive.google.com/file/d/1dofgP1ito8iGzOJCMaMPUjTPLLqEfulH/view?usp=drivesdk

Face Detection using OpenCV

This project implements Face Detection on both images and real-time video streams using OpenCV’s Deep Neural Network (DNN) module with a pre-trained deep learning model.

Features

Detects faces in images with bounding boxes and confidence scores

Real-time face detection using webcam feed

Adjustable confidence threshold to filter weak detections

Outputs detection results directly in the terminal and with bounding boxes on screen


Tech Stack Usage

Python
OpenCV
NumPy
Imutils


Run the scripts from the command prompt:

Detect faces in an image:

python detect_faces.py --image sample1.jpg --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caffemodel

Real-time face detection via webcam:

python detect_faces_video.py --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caffemodel

Applications

Surveillance systems,
Photo tagging,
User authentication,
Human-computer interaction,

