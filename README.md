# 🧠 Deep Learning Projects

This repository contains implementations of three core deep learning tasks:  
1. Perceptron Programming  
2. Feedforward Neural Network Training  
3. Convolutional Neural Network (CNN) for Face Recognition  

Each task demonstrates key learning outcomes from basic supervised learning algorithms to real-world applications in image-based recognition systems.

---

## 📘 Table of Contents

- [1. Perceptron Programming](#1-perceptron-programming)
- [2. Neural Network Training](#2-neural-network-training)
- [3. Convolutional Neural Network (CNN)](#3-convolutional-neural-network-cnn)
- [4. Deliverables](#4-deliverables)

---

## 1. 📌 Perceptron Programming

### 📝 Description

A Python implementation of the **single-layer perceptron algorithm** using a small dataset of 13 samples with 3 features each. The goal is to classify binary outcomes based on input features using different learning rates.

### 📊 Dataset

- `train_data`: 8 samples  
- `test_data`: 5 samples  
- Each sample: `[bias_term, feature1, feature2, label]`

### ⚙️ Objectives

- Start with weights `W = [0, 0, 0]` and bias = 0
- Train using three different learning rates:
  - η = 0.1  
  - η = 0.2  
  - η = 0.3
- Evaluate the final weights and classification accuracy

---

## 2. 🔁 Neural Network Training

### 📝 Description

A manually implemented feedforward **neural network** with:
- 3 input features: x1, x2, x3  
- 1 hidden layer with 2 neurons  
- 1 output neuron  
- Activation function: **Sigmoid**  
- Loss function: **Mean Squared Error (MSE)**  
- Training method: **Stochastic Gradient Descent (SGD)**

### 🔢 Initial Parameters

- Weights:  
  `W1=0.2, W2=-0.3, W3=0.4, W4=0.1, W5=-0.5, W6=0.2, W7=-0.3, W8=-0.2`  
- Biases:  
  `b1=-0.4, b2=0.2, b3=0.1`

### 📊 Dataset

- **moonDataset.csv**  
- 200 samples with 3 input features and binary labels (0 or 1)

### 📈 Output

- Model trains for **20 epochs**
- A loss curve is plotted to visualize performance over time

---

## 3. 🧠 Convolutional Neural Network (CNN)

### 📝 Description

Build a CNN-based **Face Recognition System** that can:
- Collect and preprocess facial image data
- Train a CNN model for face classification
- Test the model on new face images
- Recognize student faces for smart attendance

### 📦 Features

- Deep CNN architecture for robust face embedding
- Real-time student identification and attendance logging
- Ready-to-deploy backend (optional: Flask, FastAPI, or web interface)

### 🎯 Applications

- Smart Attendance Management System (SAMS)
- University automation and surveillance

---

## 4. 📦 Deliverables

### ✅ Perceptron Programming
- `perceptron.py`
- Accuracy results for each learning rate
- Table of weight updates

### ✅ Neural Network Training
- `neural_network.py`
- Plot of loss vs. epochs
- Weight updates after training

### ✅ CNN for Face Recognition
- `cnn_model.py`
- Preprocessed face data
- Trained model file
- Test results and performance report
