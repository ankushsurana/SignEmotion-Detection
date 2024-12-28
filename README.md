# Sign Language and Emotion Detection System

This repository contains a Jupyter Notebook implementation of the **Sign Language and Emotion Detection System**. The project uses Convolutional Neural Networks (CNNs) to identify hand signs and facial emotions from images and live video streams. It leverages TensorFlow and OpenCV for real-time predictions and interactive visualizations.


## Project Overview

The system detects:
1. **Sign Language Alphabets**: Recognizes American Sign Language (A-Z, excluding J and Z).
2. **Facial Emotions**: Identifies seven basic emotions - Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral.


## Features

- **Real-Time Detection**: Live video feed processed to detect both sign language and facial emotions.
- **Data Augmentation**: Enhanced training with techniques like rotation, zoom, and flipping.
- **Custom Preprocessing**: Image normalization and resizing for optimal model performance.
- **Model Performance**: Achieved high accuracy with fine-tuned hyperparameters.


## Dataset

- **Sign Language**: `sign_mnist_train.csv` and `sign_mnist_test.csv` datasets.
- **Emotion Recognition**: `fer2013_training_onehot.csv` and `fer2013_publictest_onehot.csv` datasets.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Sign-Emotion-Detection.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn tensorflow opencv-python
   ```

## Usage

1. **Load the Notebook**: Open the Jupyter Notebook to view and execute the code.
2. **Training and Evaluation**:
   - Train the models on the provided datasets.
   - Evaluate accuracy using validation data.
3. **Real-Time Detection**:
   - Run the live video feed cell to detect sign language and facial emotions in real-time.
