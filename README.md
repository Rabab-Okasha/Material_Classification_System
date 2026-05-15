# Material Stream Identification System

A Machine Learning project for automated material classification using computer vision and handcrafted feature extraction techniques. The system classifies different material categories from images to support smart recycling and waste-sorting applications.

---

## Project Overview

This project implements a complete Machine Learning pipeline for material classification, including:

- Dataset preprocessing
- Data augmentation
- Feature extraction
- Feature normalization
- Model training and evaluation
- Visualization and analysis

The system uses image-processing techniques and classical ML models to identify different waste/material types from images.

---

## Features

- Image preprocessing and augmentation
- Automatic dataset balancing
- HOG, HSV Histogram, and LBP feature extraction
- Feature scaling using StandardScaler
- Dimensionality reduction with PCA
- Classification using:
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Hyperparameter tuning with RandomizedSearchCV
- Performance evaluation using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix
- Data visualization and analysis

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Scikit-learn
- Scikit-image
- Albumentations
- Matplotlib

---

## Feature Extraction Techniques

### HOG (Histogram of Oriented Gradients)
Captures object shape and edge structures.

### HSV Color Histogram
Captures color distribution information useful for distinguishing materials.

### LBP (Local Binary Pattern)
Captures texture patterns in images.

The extracted features are combined into a single feature vector for improved classification performance.

---

## Data Augmentation Techniques

To improve model generalization and balance the dataset, the following augmentations were applied:

- Horizontal Flip
- Rotation
- Brightness & Contrast Adjustment
- Hue & Saturation Adjustment
- Gaussian Blur

---

## Machine Learning Models

### Support Vector Machine (SVM)
Used for high-dimensional feature classification.

### K-Nearest Neighbors (KNN)
Used as a comparative baseline model.

Hyperparameter optimization was performed using RandomizedSearchCV.

---

## Project Pipeline

1. Load and preprocess dataset
2. Balance dataset using augmentation
3. Split data into training and validation sets
4. Extract image features
5. Normalize feature vectors
6. Apply PCA
7. Train ML models
8. Evaluate model performance
9. Visualize results

---

## Contributors
- [Malak Hassan](https://github.com/Malakhassan8)
- [Nour Hassan](https://github.com/Nourhasann)
- [Nour Mohamed](https://github.com/Nour131)
