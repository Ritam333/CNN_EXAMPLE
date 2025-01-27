# CNN and ANN Implementation for CIFAR-10 Dataset

This project demonstrates the implementation of both Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) to classify images from the CIFAR-10 dataset. CIFAR-10 is a collection of 60,000 32x32 color images divided into 10 classes, commonly used for image classification tasks.

## Overview

- **Data Preprocessing**:
  - The CIFAR-10 images are normalized to improve model performance.
  - Data is reshaped for compatibility with ANN and CNN architectures.
- **Artificial Neural Network (ANN)**:
  - A basic feedforward network with fully connected layers.
  - Uses sigmoid activation functions.
  - Trained on flattened CIFAR-10 images.
- **Convolutional Neural Network (CNN)**:
  - Employs convolutional layers with ReLU activation to extract features.
  - Includes max-pooling layers for dimensionality reduction.
  - Fully connected layers perform the final classification.

## Steps in the Code

1. **Dataset Loading**:
   - CIFAR-10 is loaded and split into training and testing sets.
2. **Data Preprocessing**:
   - Images are normalized and reshaped as required.
3. **Model Training**:
   - ANN is trained for 2 epochs.
   - CNN is trained for 1 epoch.
4. **Model Evaluation**:
   - Both models are evaluated on the test dataset for accuracy.
5. **Prediction**:
   - Labels are predicted using the trained ANN model.

## Outputs

- Training accuracy and loss are displayed for both models.
- Evaluation results highlight model performance on unseen data.
- A sample image from the dataset is visualized during preprocessing.

---

This project serves as a simple implementation to compare ANN and CNN performance on image classification tasks.
