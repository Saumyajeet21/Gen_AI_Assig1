**# Neural Network Implementation from Scratch

## Generative AI Lab — Practice Lab Neural Network 1

### Student Information

- **Name:** Saumyajeet Singh Bhati
- **PRN:** 202401110065
- **Batch:** A1
- **Course:** Generative AI Lab
- **Department:** CSE (AIML)
- **Class:** T.Y. Tech

---

## 1. Project Overview

This project implements a **feedforward neural network from scratch using Python and NumPy**.

The purpose of this practical is to understand the internal working of a neural network without using high-level deep learning frameworks such as:

- TensorFlow
- PyTorch
- Keras

The implementation covers forward propagation, activation functions, loss calculation, backpropagation and gradient descent.

---

## 2. Dataset

The **Mobile Price Classification** dataset from Kaggle is used.

### Kaggle Dataset

https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

The dataset contains smartphone specifications and a target variable called `price_range`.

### Dataset Details

- **Total samples:** 2000
- **Input features:** 20
- **Output classes:** 4
- **Problem type:** Multi-class classification

### Target Classes

| Class | Price Category |
|---:|---|
| 0 | Low Cost |
| 1 | Medium Cost |
| 2 | High Cost |
| 3 | Very High Cost |

---

## 3. Objective

The objective of this practical is to build a neural network that predicts the price category of a smartphone based on its technical specifications.

The model uses features such as:

- Battery power
- RAM
- Internal memory
- Clock speed
- Number of processor cores
- Camera specifications
- Screen dimensions
- Pixel resolution
- Mobile weight
- 3G/4G support
- Wi-Fi
- Bluetooth
- Touchscreen

---

## 4. Neural Network Architecture

The implemented architecture is:

```text
Input Layer
    ↓
20 Neurons
    ↓
Hidden Layer 1
32 Neurons + ReLU
    ↓
Hidden Layer 2
16 Neurons + ReLU
    ↓
Output Layer
4 Neurons + Softmax**
