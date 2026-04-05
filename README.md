# deep-learning-architectures

This repository contains my work for a deep learning assignment exploring multiple neural network architectures using Keras.

## Project Contents

This project includes:

- **Part A:** Multilayer Perceptron (MLP) using the MNIST dataset
- **Part B:** Convolutional Neural Network (CNN) using the Fashion-MNIST dataset
- **Part C:** Recurrent Neural Network (LSTM) using the IMDB sentiment dataset
- **Part E:** Reflection on model effectiveness, training challenges, and real-world applications

## Summary of Results

### Part A: MLP on MNIST
The MLP performed very well on handwritten digit classification. Training and validation accuracy improved steadily, with only slight signs of overfitting near the end.

### Part B: CNN on Fashion-MNIST
The CNN achieved strong performance on clothing image classification and outperformed a basic dense-network approach for image data. The confusion matrix showed that the model sometimes confused visually similar clothing categories.

### Part C: LSTM on IMDB
The LSTM successfully classified movie reviews by sentiment and showed how recurrent models can process text sequences. The model performed well, although it showed more overfitting than the image-based models.

## Tools Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

## Files

- `deep-learning-architecture.ipynb` – main notebook containing all required parts of the assignment

## Reflection

This project showed that different deep learning architectures are better suited for different kinds of data. MLPs worked well for simple image classification, CNNs were strongest for image feature extraction, and LSTMs were appropriate for sequence-based text tasks.
