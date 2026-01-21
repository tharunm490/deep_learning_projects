# Handwritten Digit Classification using ANN

This project implements a **Handwritten Digit Classification system** using an **Artificial Neural Network (ANN)** built with **Keras and TensorFlow**.

The goal is to classify handwritten digits (0–9) by learning patterns from pixel values using a **fully connected neural network**, without using Convolutional Neural Networks (CNN).

---

## 🚀 Project Overview

Handwritten digit classification is a classic machine learning problem.  
In this project, digit images are **flattened** and fed into an ANN to perform **multiclass classification**.

This project is created as part of my **deep learning learning journey**, focusing on understanding how ANN models behave on image data.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📂 Dataset

- Handwritten digit images (0–9)
- Image size: **28 × 28 pixels**
- Pixel values represent grayscale intensity
- Target classes: **10 (digits 0 to 9)**

_(Dataset used only for learning and practice purposes)_

---

## 🔄 Workflow

1. Load the dataset
2. Normalize pixel values
3. Reshape images
4. Flatten image data
5. Build ANN model
6. Train the model
7. Evaluate performance
8. Predict digit classes

---

## 🧠 Model Architecture

- Input Layer:
  - Flattened image (28 × 28 → 784 features)
- Hidden Layers:
  - Fully connected Dense layers
  - Activation function: ReLU
- Output Layer:
  - Dense layer with Softmax activation
  - 10 output neurons (digits 0–9)

---

## 📊 Results

- The ANN successfully classifies handwritten digits
- Achieves reasonable accuracy for a basic ANN model
- Emphasis is on **conceptual understanding**, not optimization

---

## 📖 Learning Outcome

- Understanding ANN-based image classification
- Difference between ANN and CNN approaches
- Handling image data with Dense layers
- Working with Softmax and categorical outputs
- Using Keras & TensorFlow effectively

---

## 👨‍💻 Author

**Tharun M**  
Deep Learning Learner

---

## ⭐ Note

This is a **beginner-friendly project** created for learning and educational purposes.
