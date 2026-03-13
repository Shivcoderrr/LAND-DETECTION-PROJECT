# Landmark Detection using TensorFlow

This project demonstrates a deep learning approach for detecting landmarks in images using TensorFlow and a pretrained MobileNetV2 model.

## Project Overview
The model performs two tasks:
1. Landmark classification
2. Bounding box prediction for landmark localization

The project demonstrates how convolutional neural networks can be used for object detection and classification tasks.

## Technologies Used
- Python
- TensorFlow
- MobileNetV2
- NumPy
- Matplotlib
- OpenCV

## Model Architecture
The model uses MobileNetV2 as a feature extractor.  
Two output heads are used:

- Classification head for landmark prediction
- Bounding box regression head for localization

## Dataset
For demonstration purposes, a synthetic dataset is generated containing simple landmark representations such as:
- Taj Mahal
- Qutub Minar

Images are generated with bounding box annotations.

## Features
- Image preprocessing pipeline
- Transfer learning using MobileNetV2
- Bounding box prediction
- Landmark classification
- Visualization of predictions

## Output
The model predicts:
- Landmark class
- Bounding box location of the detected landmark

## Author
Shiv
AI/ML Enthusiast

