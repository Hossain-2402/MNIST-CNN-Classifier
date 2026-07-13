# Handwritten Digit Recognition using CNN (PyTorch)

A Convolutional Neural Network (CNN) built from scratch using **PyTorch** to classify handwritten digits (0–9) from the **MNIST** dataset.

---

## Project Overview

This project demonstrates an end-to-end image classification pipeline using a Convolutional Neural Network.

The model learns to recognize handwritten digits by extracting image features through convolutional layers and classifying them into one of the ten digit classes.

---

## Features

- CNN built from scratch using PyTorch
- Trained on the MNIST dataset
- Image preprocessing and normalization
- Adam optimizer
- Cross Entropy Loss
- Model evaluation on unseen test images
- Sample prediction visualization

---

## Model Architecture

```
Input Image (1 × 46 × 46)
        │
Conv2D (1 → 32)
        │
ReLU
        │
MaxPool
        │
Conv2D (32 → 64)
        │
ReLU
        │
MaxPool
        │
Conv2D (64 → 128)
        │
ReLU
        │
Flatten
        │
Linear (12800 → 128)
        │
ReLU
        │
Linear (128 → 64)
        │
ReLU
        │
Linear (64 → 32)
        │
ReLU
        │
Linear (32 → 10)
```

---

## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Torchvision

---

## Training

- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Epochs: 10
- Activation Function: ReLU
- Pooling: MaxPooling

---

## Dataset

**MNIST (Modified National Institute of Standards and Technology)**

- 70,000 handwritten digit images
- 10 classes (0–9)
- Grayscale images

---

## Sample Predictions

The repository includes several prediction examples showing both successful classifications and a misclassified example to demonstrate real-world model behavior.

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Convolutional Neural Networks (CNNs)
- Feature extraction using convolution
- Max Pooling
- ReLU activation
- Backpropagation
- Cross Entropy Loss
- Adam Optimizer
- Training and evaluating deep learning models with PyTorch

---

## Repository Structure

```
├── MNIST.ipynb
├── README.md
├── images/
│   ├── pred_4.png
│   ├── pred_6.png
│   ├── pred_9.png
│   └── loss_graph.png
```

---

## Author

**M. Hossain Ibna Ehsan**

