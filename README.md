# Deep Learning-Based Diagnostic System for Pneumonia

## Overview

This project develops an AI-assisted pneumonia detection system using chest X-ray images. The system classifies images into **Normal** or **Pneumonia** and applies **Grad-CAM explainability** to show the image regions that influenced the prediction.

This project compares three deep learning models: **Custom CNN, ResNet50, and EfficientNetB0**. EfficientNetB0 was selected as the best model due to its strong screening performance.

## Project Objectives

1. To develop deep learning models for classifying chest X-ray images into Normal and Pneumonia classes.
2. To compare Custom CNN, ResNet50, and EfficientNetB0 using accuracy, precision, recall, F1-score, and AUC.
3. To apply Grad-CAM to visualize the regions that influence the model prediction.

## System Workflow

1. Upload chest X-ray image
2. Pre-process image
3. Classify image using deep learning model
4. Display prediction result
5. Generate Grad-CAM heatmap for explainability

## Best Model Performance

| Metric               | EfficientNetB0 Result |
| -------------------- | --------------------: |
| Accuracy             |                 82.0% |
| Precision            |                 75.8% |
| Recall / Sensitivity |                 94.0% |
| F1-Score             |                 83.9% |
| AUC                  |                93.32% |
| Final Score          |                0.8601 |

## Why EfficientNetB0?

EfficientNetB0 was selected because it achieved the strongest screening performance, especially in detecting pneumonia cases. Its high recall helps reduce missed pneumonia cases, which is important for medical screening.

## Tools and Technologies

* Python
* TensorFlow / Keras
* Jupyter Notebook
* Anaconda
* Matplotlib / Seaborn
* Grad-CAM

## Dataset

This project uses the Chest X-Ray Images (Pneumonia) dataset from Kaggle. The dataset contains two classes:

* Normal
* Pneumonia

## Application Potential

This system has potential as an AI-assisted pneumonia screening support tool for clinics, hospitals, and low-resource healthcare settings. It can support early screening by providing prediction results with visual heatmap explanation.

## Disclaimer

This project is a research prototype for educational and diagnostic support purposes only. It is not a replacement for professional medical diagnosis.

## Developed By

**Nur Syuhaila Binti Ismail**
Bachelor of Engineering (Computer Engineering) with Honors
Faculty of Intelligent Computing
Universiti Malaysia Perlis (UniMAP)

Supervisor: **Assoc. Prof. Ir. Ts. Dr. Junita Mohd Nordin**
