# Brain Tumor MRI Classification Using Deep Learning and MobileNetV2D

## Overview

This project implements a deep learning-based brain tumor classification system using MRI images and MobileNetV2 transfer learning.

The model classifies MRI scans into four categories:

* Glioma
* Meningioma
* Pituitary Tumor
* No Tumor

## Dataset

Brain Tumor MRI Dataset:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Dataset Statistics:

* Training Images: 5,600
* Testing Images: 1,600
* Total Images: 7,200
* Number of Classes: 4

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Deep Learning Model

Transfer Learning Architecture:

* MobileNetV2
* Global Average Pooling
* Dense Layer (128 neurons)
* Dropout Layer
* Softmax Output Layer

## Workflow

1. Dataset Loading
2. Image Preprocessing
3. Data Augmentation
4. Feature Extraction using MobileNetV2
5. Classification Training
6. Model Evaluation
7. Confusion Matrix Analysis

## Results

The MobileNetV2 transfer learning model was trained for brain tumor MRI classification across four classes:

- Glioma
- Meningioma
- Pituitary Tumor
- No Tumor

The project includes data preprocessing, model training, evaluation, and visualization using confusion matrix analysis.

## Project Files

* brain_tumor_segmentation_classification.py
* requirements.txt
* dataset/dataset_link.txt

## Future Improvements

* Hyperparameter tuning
* Advanced data augmentation
* Model performance optimization
* Explainable AI (XAI) techniques
* Deployment using Streamlit or Flask
* Comparative analysis with other CNN architectures

## Author

Akshay Kedare

Data Analytics Student with interests in Machine Learning, Deep Learning, Computer Vision, and Artificial Intelligence.
