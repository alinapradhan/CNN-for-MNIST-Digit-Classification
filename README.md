# CNN-for-MNIST-Digit-Classification


This project uses a Convolutional Neural Network (CNN) built with Keras to classify handwritten digits from the MNIST dataset.

## 📊 Dataset

- **Source**: [MNIST](http://yann.lecun.com/exdb/mnist/)
- 60,000 training images, 10,000 test images
- Grayscale 28x28 pixel digits (0-9)

## 🧠 Model Architecture

The CNN model consists of:
- `Conv2D` and `MaxPooling2D` layers for feature extraction
- `Flatten` layer to prepare data for dense layers
- Fully connected `Dense` layers for classification

## 🚀 Getting Started

### Requirements

Install dependencies:

```bash
pip install -r requirements.txt

