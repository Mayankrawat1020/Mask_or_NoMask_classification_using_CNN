# Mask Classification Model

This repository contains code for a deep learning model that classifies images into two categories: `masked` and `unmasked`. The model is built using TensorFlow and Keras and is trained on images resized to 256x256 pixels.

## Features
- **Convolutional Neural Network (CNN):** The model uses multiple convolutional layers for feature extraction.
- **Dropout Layers:** To reduce overfitting, dropout is applied during training.
- **Binary Classification:** The model outputs predictions for two classes: masked and unmasked.

## Requirements

Install the following dependencies:
```bash
pip install tensorflow numpy opencv-python
```

## Model Architecture
The model architecture consists of:
1. Three convolutional layers with ReLU activations and max-pooling layers.
2. Fully connected dense layers with dropout to prevent overfitting.
3. A final dense layer with a softmax activation for classification.


## Usage
1. Clone the repository and navigate to the project directory.
2. Prepare your dataset with images of masks and non-masks.
3. Replace `X_train`, `Y_train`, and `X_test` with your dataset.
4. Run the script to train the model.
5. Use the saved model (`mask_classification_model.h5`) for predictions.

## Acknowledgments
This project uses TensorFlow and OpenCV for image processing and deep learning tasks. Special thanks to the TensorFlow team for their excellent tools and documentation.

---

Feel free to contribute or raise issues if you encounter any problems!
