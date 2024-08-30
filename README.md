# Flower Image Classification with TensorFlow and TensorFlow Lite

This project demonstrates how to classify images of flowers using a `tf.keras.Sequential` model in TensorFlow and convert the trained model to TensorFlow Lite for on-device machine learning. The tutorial covers essential concepts including data loading, model building, training, overfitting mitigation, and TensorFlow Lite model conversion.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Model Conversion](#model-conversion)
6. [Inference](#inference)
7. [License](#license)
8. [Contact](#contact)

## Project Overview

This project includes a Jupyter Notebook (`image_classification.ipynb`) that walks through the following steps:

- **Loading and Exploring Data**: Downloading and visualizing flower images.
- **Data Preprocessing**: Rescaling and augmenting the image data.
- **Building the Model**: Creating and training a Convolutional Neural Network (CNN).
- **Evaluating the Model**: Analyzing training and validation performance.
- **Overfitting Mitigation**: Implementing data augmentation and dropout.
- **Converting to TensorFlow Lite**: Converting the Keras model to TensorFlow Lite format for efficient on-device inference.
- **Running Inference**: Using the TensorFlow Lite model to make predictions on new images.

## Dataset

The dataset used in this project consists of approximately 3,700 images of flowers categorized into the following five classes:

- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

The dataset can be automatically downloaded and extracted via the notebook.

## Setup

To get started, ensure you have Python 3.x installed. Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
