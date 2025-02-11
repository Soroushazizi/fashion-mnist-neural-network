# Fashion MNIST Neural Network from Scratch

## Description
A custom implementation of a fully connected neural network for Fashion MNIST classification using PyTorch, built from scratch without using PyTorch's neural network modules. The project includes custom implementations of activation functions, loss functions, and training algorithms.

## Project Features
- Custom neural network implementation without using nn.torch
- Implementation of activation functions (ReLU, Softmax)
- Custom Cross-Entropy loss function
- SGD optimizer implementation from scratch
- Fashion MNIST dataset visualization and processing
- Training and testing pipeline
- Achievement of ~80% accuracy on test data

## Technical Details
- **Input Layer**: 784 neurons (28x28 flattened images)
- **Hidden Layers**: Fully connected layers with ReLU activation
- **Output Layer**: 10 neurons with Softmax activation
- **Batch Size**: 64
- **Data Preprocessing**: Normalization to [-1, 1] range
- **Learning Algorithm**: Stochastic Gradient Descent (SGD)

## Dataset
The Fashion MNIST dataset consists of:
- 60,000 training images
- 10,000 test images
- 10 classes of fashion items
- 28x28 grayscale images

## Requirements
- Python 3.x
- PyTorch
- NumPy
- Matplotlib

## Usage
1. Clone the repository
2. Install dependencies
3. Run the training script:
```bash
python fmnn.py
```

## Author
Soroush Azizi

## Course Information
Machine Learning Course Project
