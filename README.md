# Alzheimer-s-Disease-Prediction-and-Brain-Region-Analysis-from-MRI-Scans
Dataset:  OASIS Alzheimer’s Detection (Kaggle) (https://www.kaggle.com/datasets/ninadaithal/imagesoasis)
Description: This dataset comprises 2D slices (61 per patient) derived from 3D MRI scans. The dataset is organized to facilitate binary classification tasks (Alzheimer’s vs. non-Alzheimer’s) and is suitable for applying 3D CNN models by stacking the 2D slices into 3D volumes.

Project Description: This project aims to develop a machine learning model to predict Alzheimer’s disease using MRI scans and analyze the brain regions contributing to the predictions. The model will focus on classifying MRI scans as Alzheimer’s or non-Alzheimer’s and visualizing important brain regions through 2D Grad-CAM overlays, providing insights into the disease's impact on the brain.
Steps to Complete the Project:
Data Preprocessing:
Load Data:
Import the 2D MRI slices and corresponding labels for Alzheimer’s detection.
Organize and stack 61 slices per patient to form 3D volumes with dimensions (H, W, 61).
Normalization:
Normalize the pixel values to ensure consistent input data across the model.
Alzheimer’s Disease Prediction:
Model Development:
Develop a 3D CNN model to classify the stacked MRI volumes as Alzheimer’s or non-Alzheimer’s.
Training:
Train the model using the stacked volumes and evaluate its performance using metrics such as Accuracy, AUC-ROC, Precision, and Recall.
Brain Region Analysis:
Generate Grad-CAM Heatmaps:
Apply Grad-CAM to the trained 3D CNN model to produce a 3D heatmap highlighting important regions across the MRI volume.
2D Visualization:
Extract 2D slices from the 3D heatmap and overlay them on the original MRI slices to visualize the key regions of importance for each patient.
Evaluation:
Classification Metrics:
Assess the model’s performance using Accuracy, Precision, Recall, F1-score, and AUC-ROC.
Region Analysis:
Evaluate the significance of the highlighted brain regions and their consistency with known Alzheimer’s pathology.

