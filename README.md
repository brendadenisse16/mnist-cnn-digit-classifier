# 🧠 MNIST CNN Digit Classifier

This repository contains a PyTorch-based solution for handwritten digit classification using Convolutional Neural Networks (CNNs).  
The project is based on a lab exercise but extended and refactored into a distinct notebook for clarity and purpose:

- 🎓 `mnist_cnn_tutorial.ipynb`: An educational, step-by-step guide that walks through the architecture, training, and evaluation process of a CNN.

## 📚 About the Project

The goal is to build a digit classifier that can accurately recognize handwritten numbers from the MNIST dataset.  
Instead of using high-level utilities like `torchvision.datasets`, we load the data from `.npz` files to mimic a real-world data ingestion setup.

Key concepts covered:

- Custom PyTorch Dataset class loading `.npz` data
- Data normalization and batching
- CNN architecture with `Conv2D`, `ReLU`, `MaxPool2D`, and `Linear` layers
- Model training with cross-entropy loss optimizer
- Accuracy evaluation and training loss visualization

---

