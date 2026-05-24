# AI Image Tampering Detection

AI-powered image tampering detection system leveraging computer vision, feature engineering, PCA, and machine learning techniques for manipulated image classification.

## Overview

This project implements a machine learning-based image tampering detection system capable of classifying images as authentic or manipulated. The system applies computer vision feature extraction techniques and machine learning algorithms to identify forgery artifacts present in digitally tampered images.

## Features

* Detection of authentic and manipulated images
* HOG, LBP, FFT, and statistical feature extraction
* PCA-based dimensionality reduction
* Machine learning classification pipeline
* Confusion matrix and ROC-AUC evaluation
* Prediction visualization and analysis

## Technologies Used

* Python
* OpenCV
* NumPy
* Scikit-learn
* Scikit-image
* Matplotlib
* Seaborn

## Workflow

1. Dataset extraction and preprocessing
2. Image resizing and grayscale conversion
3. Feature extraction using HOG, LBP, FFT, and statistical descriptors
4. Feature scaling and dimensionality reduction using PCA
5. Machine learning model training and evaluation
6. Prediction visualization and performance analysis

## Dataset

The dataset contains authentic and manipulated images including:

* Copy-move forgery
* Image splicing
* Inpainting-based manipulation

## Project Structure

```bash id="6eq4k2"
AI_Image_Tampering_Detection/
│
├── README.md
├── requirements.txt
├── training.ipynb
├── results/
│   ├── evaluation.png
│   └── predictions.png
```

## Future Improvements

* CNN and deep learning integration
* Real-time image forgery detection
* Transformer-based vision architectures
* Larger balanced datasets for improved accuracy

## Author

Rishitha Pulaparthi
