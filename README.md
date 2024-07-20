# CNN-on-Fashion-MNIST-Dataset

This project demonstrates the application of a Convolutional Neural Network (CNN) on the Fashion MNIST dataset to classify images into 10 different categories. The CNN model is trained, validated, and tested, with performance metrics and visualizations provided.

# Dataset Description

Fashion-MNIST: Zalando's article images dataset.

Training Set: 60,000 examples.

Test Set: 10,000 examples.

Image Size: 28x28 pixels, grayscale.

Labels: 10 categories (T-shirt/top, trousers, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).

# Pre-processing

Resizing: Standardizing image size.

Normalization: Scaling pixel values to [0, 1].

Data Augmentation: Applied rotation, shifting, shear, zoom, and horizontal flip to increase dataset size and model robustness.

## CNN Architecture

# Layers:

Two convolutional layers with ReLU activation.

Max-pooling layers for down-sampling.

Fully connected layers for classification.

Activation: ReLU for non-linearity.

Pooling: Max-pooling for reducing spatial dimensions and computational complexity.

# Training Process

Optimizer: Adam.

Loss Function: Sparse categorical cross-entropy.

Hyperparameters: Learning rate, epochs, and batch size (not extensively tuned).

# Performance Metrics

Test Accuracy: 0.887.




