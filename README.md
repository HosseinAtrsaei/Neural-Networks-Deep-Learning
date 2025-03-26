# Neural-Networks-Deep-Learning
This repository contains the implementation and report for HW#4 of the **Intelligent Systems** course at the **University of Tehran**.  The assignment focuses on theoretical understanding and practical implementation of multi-layer neural networks, convolutional neural networks (CNNs), and transfer learning using EfficientNet.

## 📌 Contents

### 🔹 Q1 – Theoretical Analysis of MLP and Backpropagation
- Step-by-step forward propagation and error calculation in a manually-defined MLP
- Backpropagation equations and parameter updates
- Full symbolic derivation and numerical results
- Python implementation to validate analytical calculations

### 🔹 Q2 – Classification on CIFAR-10 with MLP & CNN
- Implemented MLP and CNN models to classify CIFAR-10 images
- Preprocessing, normalization, and one-hot encoding
- Comparison of activation functions: `ReLU`, `SeLU`, `tanh`, `sigmoid`
- Evaluation of different:
  - Loss functions: Cross-Entropy, MAE, MSE
  - Optimizers: SGD, Adam, RMSprop
  - Architectures with and without: BatchNorm, MaxPooling, Dropout
- Accuracy & confusion matrices reported for each setup

### 🔹 Q3 – Transfer Learning with EfficientNet
- Introduction to EfficientNet architecture
- Image classification using pretrained `EfficientNetB0` model
- Fine-tuning on custom datasets with two new classes
- Applied early stopping and custom rejection logic for low-confidence predictions
- Evaluation of model performance with high validation accuracy
