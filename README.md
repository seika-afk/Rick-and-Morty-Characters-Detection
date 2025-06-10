# Rick and Morty Character Detection using Deep Learning

## Overview
This project focuses on detecting and classifying characters from the popular animated series "Rick and Morty" using deep learning techniques. The implementation leverages TensorFlow and Keras for model training, along with data augmentation to improve generalization. The dataset consists of labeled images of characters like Rick, Morty, Jerry, Summer, and Beth.

## Model Used :
- MobileNet
- Inception
- Efficientnet
- CNN

## Features
- **Data Preparation**: Organizes images into structured CSV files for easy loading.
- **Image Augmentation**: Uses `ImageDataGenerator` to enhance training data with transformations like rotation, zoom, and flipping.
- **Exploratory Data Analysis (EDA)**: Includes visualizations of label distributions and dataset statistics.
- **Model Training**: Utilizes a CNN (Convolutional Neural Network) for character classification.
- **Evaluation**: Assesses model performance on test data.

## Dataset
The dataset is sourced from Kaggle and contains:
- **Training Images**: 9,413 images across 5 classes (Rick, Morty, Jerry, Summer, Beth).
- **Test Images**: 375 images with unknown labels for evaluation.

### Class Distribution (Training Data)
- Rick: 3,128 images
- Morty: 2,620 images
- Jerry: 1,946 images
- Summer: 1,237 images
- Beth: 482 images

## Setup
1. **Environment**: Requires Python 3.7+, TensorFlow 2.x, and dependencies listed in `requirements.txt`.
   ```bash
   pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
