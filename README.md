# Fashion-Image-Classification-CNN
Deep Learning project for automatic clothing classification and product tagging using CNNs in PyTorch.
# AI Clothing Classification using CNN

##  Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to automate product tagging for an e-commerce clothing store.  
The model classifies clothing images into multiple categories and evaluates performance using accuracy, precision, and recall.

---

##  Objectives
- Build a CNN model for multi-class image classification
- Automate product tagging
- Train the model (2 epochs for fast experimentation)
- Store predictions in a list named `predictions`
- Evaluate performance using:
  - Accuracy
  - Per-class Precision
  - Per-class Recall

---

##  Model Architecture
The CNN includes:
- Conv2D Layer
- ReLU Activation
- MaxPooling Layer
- Flatten Layer
- Fully Connected (Linear) Layer

---

##  Evaluation Metrics
- CrossEntropyLoss
- Adam Optimizer
- Accuracy
- Precision (per class)
- Recall (per class)
