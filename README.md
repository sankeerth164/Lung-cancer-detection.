# Lung-cancer-detection.
CNN-based deep learning model to classify histopathological images of lung and colon cancer into Adenocarcinoma, Large Cell Carcinoma, Squamous Cell Carcinoma, and Normal tissue. Achieved ~95% validation accuracy using TensorFlow/Keras, data augmentation, and class balancing.


Overview
This project implements a Convolutional Neural Network (CNN) to classify histopathological images of lung and colon cancer into four categories:
1. Adenocarcinoma
2. Large Cell Carcinoma
3. Squamous Cell Carcinoma
4. Normal Tissue

The model aims to assist in early cancer diagnosis by automating the classification process, reducing human error, and supporting medical professionals.

Dataset
Source: Kaggle – Lung and Colon Cancer Histopathological Images
Contains microscopic images of cancerous and non-cancerous tissue samples.

Features
Custom CNN architecture with convolutional, pooling, dropout, and batch normalization layers.
Data preprocessing & augmentation (rotation, flipping) to improve robustness.
Class balancing to address dataset imbalance.
Performance metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix.
Early stopping with Adam optimizer for stable convergence.

Tech Stack
Language: Python
Libraries: TensorFlow/Keras, OpenCV, NumPy, Pandas, Matplotlib, scikit-learn
Environment: Google Colab

Results
Validation Accuracy: ~95%
Balanced performance across all classes with high precision and recall.



Note: 
Here I am uploading both file .ipynb and .py.

