# Brain-Tumor-Detector
Project Overview

This project focuses on automatic brain tumor detection from MRI images using Deep Learning techniques. The model aims to classify brain MRI scans into tumor and non-tumor categories (or multiple tumor types) to assist in early diagnosis and clinical decision support.

The entire workflow — from data preprocessing to model training and evaluation — is implemented using Python and CNN-based architectures, trained and tested in Google Colab.


---

Objectives

Develop a deep learning model to detect brain tumors from MRI images

Perform image preprocessing and data augmentation

Train and evaluate a CNN-based classification model

Achieve high accuracy while maintaining generalization

Provide a reproducible and well-documented ML pipeline



---

Model & Technique Used

Convolutional Neural Network (CNN)

Transfer Learning (optional – VGG16 / ResNet / MobileNet)


CNNs are well-suited for image-based medical diagnosis due to their ability to automatically extract spatial features from MRI scans.


---

Project Structure

brain-tumor-detection/
│
├── notebooks/
│   └── brain_tumor_detection.ipynb
│
├── data/                 # MRI dataset (not included due to size)
├── models/               # Saved model files (ignored)
├── images/               # Sample MRI images
├── README.md
├── requirements.txt
└── .gitignore


---

Tech Stack

Python 3

Google Colab / Jupyter Notebook

Libraries Used:

TensorFlow / Keras

NumPy

Pandas

OpenCV

Matplotlib / Seaborn

Scikit-learn




---

Workflow

1. Dataset loading and exploration


2. Image preprocessing and normalization


3. Data augmentation to prevent overfitting


4. Train-test split


5. CNN model building and compilation


6. Model training and validation


7. Performance evaluation and visualization




---
Model Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix


These metrics help assess the reliability of the model for medical image classification tasks.


---

Results

The trained model successfully learns discriminative features from MRI images and demonstrates strong performance on validation data. Results may vary depending on dataset size, quality, and model configuration.


