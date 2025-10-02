# MNIST Handwritten Digit Recognition

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://www.tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Deep learning CNN model for recognizing handwritten digits (0-9) from the MNIST dataset

## 📖 Overview

A convolutional neural network implementation that achieves **99%+ accuracy** on the classic MNIST handwritten digit classification task. The model uses a simple yet effective CNN architecture with dropout regularization to prevent overfitting.

## 🎯 Performance

- **Test Accuracy**: 99.16%
- **Architecture**: 2 Conv layers + MaxPooling + Dropout + Dense layers
- **Training**: Early stopping with validation monitoring
- **Dataset**: 60,000 training images, 10,000 test images (28x28 grayscale)

## 🛠️ Technologies

- **Python 3.8+**
- **TensorFlow/Keras** - Deep learning framework
- **NumPy** - Numerical computing
- **Matplotlib** - Visualization
- **extra-keras-datasets** - Extended datasets (EMNIST support)

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/mnist-digit-recognition.git
cd mnist-digit-recognition

# Install dependencies
pip install tensorflow numpy matplotlib extra-keras-datasets
