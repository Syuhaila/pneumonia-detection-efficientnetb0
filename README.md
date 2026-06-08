# Deep Learning-Based Diagnostic System for Pneumonia

## Overview

This project focuses on developing a pneumonia detection system using chest X-ray images. The system is designed to classify an uploaded chest X-ray image as either **Normal** or **Pneumonia**. It also includes Grad-CAM visualization to show the image areas that influenced the prediction.

Three deep learning models were developed and compared in this project: **Custom CNN, ResNet50, and EfficientNetB0**. Based on the overall performance, EfficientNetB0 was selected as the best model.

## Project Objectives

1. To develop deep learning models for classifying chest X-ray images into Normal and Pneumonia classes.
2. To compare the performance of Custom CNN, ResNet50, and EfficientNetB0.
3. To use Grad-CAM to provide visual explanation for the model prediction.

## System Workflow

The system follows these main steps:

1. A chest X-ray image is uploaded.
2. The image is resized and pre-processed.
3. The trained model classifies the image.
4. The system displays the prediction result.
5. Grad-CAM generates a heatmap to show the focused image region.

## Best Model Performance

| Metric               | EfficientNetB0 Result |
| -------------------- | --------------------: |
| Accuracy             |                 82.0% |
| Precision            |                 75.8% |
| Recall / Sensitivity |                 94.0% |
| F1-Score             |                 83.9% |
| AUC                  |                93.32% |
| Final Score          |                0.8601 |

## Model Selection

EfficientNetB0 was chosen as the best model because it achieved the strongest overall screening performance. The model recorded a high recall value of **94.0%**, which is important because it means fewer pneumonia cases were missed.

## Tools Used

* Python
* TensorFlow / Keras
* Jupyter Notebook
* Anaconda
* Matplotlib / Seaborn
* Grad-CAM

## Dataset

The project used the **Chest X-Ray Images (Pneumonia)** dataset from Kaggle. The dataset contains two image classes:

* Normal
* Pneumonia

## Application

This project can be used as a basic screening support system for pneumonia detection from chest X-ray images. It may be useful for educational, research, or early prototype development related to medical image analysis.

## Disclaimer

This project is developed for academic and research purposes only. It is not intended to replace professional medical diagnosis.

## Developed By

**Nur Syuhaila Binti Ismail**
Bachelor of Engineering (Computer Engineering) with Honors
Faculty of Intelligent Computing
Universiti Malaysia Perlis (UniMAP)

Supervisor: **Assoc. Prof. Ir. Ts. Dr. Junita Mohd Nordin**
