# Image Classification Model from Scratch – Fashion MNIST

## Introduction
This project implements a **Deep Learning image classification model** from scratch using the **Fashion MNIST dataset**.  

The goal is to classify images of clothing items into different categories using a neural network built with **TensorFlow/Keras**.

---

# Dataset
The **Fashion MNIST dataset** contains grayscale images of clothing items such as:

- T-shirts / Tops
- Trousers
- Pullovers
- Dresses
- Coats
- Sandals
- Shirts
- Sneakers
- Bags
- Ankle boots

Each image is 28x28 pixels in size.

---

# Project Workflow

### 1. Data Preprocessing
- Load Fashion MNIST dataset
- Normalize pixel values (0–255 → 0–1)
- Reshape data for neural network input

---

### 2. Model Architecture
A Neural Network is built from scratch using:

- Input layer (flattened images)
- Fully connected hidden layers
- Activation functions (ReLU, Softmax)

---

### 3. Model Training
- Train the model using training dataset
- Optimize using loss function (e.g., categorical crossentropy)
- Use optimizer like Adam

---

### 4. Model Evaluation
Evaluate performance using:

- Accuracy
- Loss curves
- Confusion matrix

---

# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

# Expected Outcome

By the end of this project, the model will be able to:

- Classify clothing images into 10 categories
- Learn visual patterns from grayscale images
- Achieve reliable accuracy on unseen test data

This project demonstrates the fundamentals of **computer vision and deep learning** using a classic benchmark dataset.
