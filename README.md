# TB Severity Prediction and Longitudinal Analysis Using Deep Learning

## Overview

This project presents a deep learning framework for analyzing chest X-ray images to estimate tuberculosis (TB) severity and monitor disease progression over time.

The system uses a ResNet18-based convolutional neural network to predict a continuous TB severity score and employs Grad-CAM for explainable AI visualization. Additionally, it supports longitudinal analysis by evaluating multiple chest X-rays and tracking severity changes across patient visits.

---

## Features

* TB Severity Prediction using Deep Learning
* Explainable AI using Grad-CAM
* Longitudinal Disease Progression Analysis
* Treatment Response Monitoring
* Interactive Gradio Interface
* Chest X-ray Image Processing

---

## Methodology

### Input

Chest X-ray image

### Preprocessing

* Resize images to 224 × 224
* Convert image to tensor format
* Data augmentation using horizontal flipping

### Deep Learning Model

* Architecture: ResNet18
* Framework: PyTorch
* Output: Continuous severity score (0–1)

### Explainable AI

Grad-CAM is used to highlight regions of the lungs that contribute to the model's prediction.

### Longitudinal Analysis

Multiple X-rays can be uploaded to analyze disease progression over time.

---

## Project Pipeline

Chest X-ray Image

↓

Image Preprocessing

↓

ResNet18 Model

↓

Severity Score Prediction

↓

Grad-CAM Visualization

↓

Longitudinal Progression Analysis

---

## Technologies Used

* Python
* PyTorch
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Gradio

---

## Results

### Severity Prediction

Example:

Severity Score: 0.78

Interpretation: Severe TB Involvement

### Grad-CAM Visualization

The system highlights important lung regions influencing the prediction.

### Longitudinal Analysis

Severity scores from multiple visits are plotted to visualize disease progression and treatment response.

---

## Future Improvements

* Lung Segmentation
* Vision Transformer Models
* Clinical Validation on Real Longitudinal Data
* Web Deployment

---

## Author

Midhunraj N P
