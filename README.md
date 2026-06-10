Drowsiness Detection and Alert System
Overview

Driver drowsiness is one of the leading causes of road accidents worldwide. This project presents a real-time Drowsiness Detection and Alert System that leverages a hybrid VGG-DenseNet deep learning architecture to identify signs of driver fatigue and issue timely alerts, thereby enhancing road safety.

The system analyzes facial features from live video streams, classifies the driver's state as drowsy or alert, and triggers alerts when drowsiness is detected. The project also integrates IoT technologies for monitoring and data visualization.

Features
Real-time driver drowsiness detection
Hybrid VGG-DenseNet deep learning model
Face and eye region analysis using computer vision
Automatic alert generation upon drowsiness detection
IoT integration using ThingSpeak
Performance comparison across multiple deep learning models
Custom-built dataset for robust training and evaluation
Dataset

A custom dataset was created specifically for this project:

42,237 images
Extracted from 69 videos

Dataset Creation Pipeline
Record videos of participants.
Extract frames from videos.
Label images into drowsy and alert categories.
Preprocess images.
Split into training, validation, and testing datasets.

Tech Stack - 
Python, 
Libraries and Frameworks, 
TensorFlow, 
Keras, 
OpenCV, 
NumPy, 
Matplotlib, 
VGG,
DenseNet, 
Hybrid VGG-DenseNet Architecture, 
IoT Tools, 
ThingSpeak, 
Wokwi
