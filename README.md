# ObjectDetection

This project implements an **object detection system for handwritten digits** using the MNIST dataset. It not only classifies digits (0–9) but also predicts their exact positions within a 75×75 image canvas. The model demonstrates combining **classification** and **localization** using TensorFlow and Keras.

## Features
- Classifies handwritten digits (0–9)
- Detects and localizes digits in a 75×75 image canvas
- Uses a **Convolutional Neural Network (CNN)** for feature extraction
- Separate dense layers for classification and bounding box regression
- Evaluation using metrics like **Intersection over Union (IoU)**
- Visualization utilities to inspect predictions 🖼️📐

## Dataset
- **MNIST dataset** (Modified National Institute of Standards and Technology)
- 28×28 grayscale images of handwritten digits
- Digits are randomly placed within a 75×75 canvas for object detection tasks

## License

This project is licensed under the MIT License.
