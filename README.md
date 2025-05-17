# Road Obstacle Detector 🚧

A deep learning project that uses Convolutional Neural Networks (CNNs) to detect road obstacles (potholes, speed bumps, etc.) from camera images — useful for autonomous driving systems and smart transportation.

## 📦 Dataset

The dataset is automatically downloaded from Kaggle:
[Road Obstacles Detection Dataset](https://www.kaggle.com/datasets/shrunmayshinde/road-obstacles-detection)

It contains labeled images of:
- Normal roads
- Potholes
- Speed bumps

## 🧠 Model

This project uses TensorFlow/Keras to build and train a CNN with the following goals:
- Classify road images into obstacle types
- Achieve lightweight inference suitable for real-time use
- Handle imbalanced datasets with `class_weight`

### Architecture Highlights:
- Input shape: 224x224 images
- Standard CNN layers with ReLU and max-pooling
- Dense output layer for classification

## 🛠️ Requirements

Make sure you have the following installed:

```bash
pip install tensorflow matplotlib scikit-learn kagglehub
