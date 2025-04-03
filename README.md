# Brain Tumor Classification

## Overview
This project uses a Convolutional Neural Network (CNN) to classify brain MRI scans into four categories:
- **Glioma Tumor**
- **Meningioma Tumor**
- **No Tumor**
- **Pituitary Tumor**

The dataset used is from Kaggle: [Brain Tumor Classification MRI](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).

## Key Metrics
- **Training Accuracy:** 98.11%
- **Validation Accuracy:** 89.19%
- **Loss (Validation):** 0.5008
- **Confusion Matrix:**
  - **True Positives (TP):** 75
  - **True Negatives (TN):** 95
  - **False Positives (FP):** 2
  - **False Negatives (FN):** 5
- **Final Model Accuracy:** 96.04%

## Results
- The CNN model successfully classifies brain tumor MRI images with high accuracy.
- The confusion matrix indicates that false positives and false negatives are minimal, ensuring reliability.
- The trained model is saved as `braintumer.h5`.

## Prediction Example
Given an MRI scan, the model predicts the tumor category with a probability distribution and selects the highest probability label.

## Next Steps
- Further optimization of hyperparameters to improve generalization.
- Exploring data augmentation techniques to increase dataset diversity.
- Deployment of the trained model using Flask or Streamlit for real-time inference.

---
📌 **Note:** Ensure the dataset is properly extracted before training to avoid file path errors.
## Author
- **Name**: Mantesh Mahesh Redekar
- **Contact**: manteshredekar1@gmail.com

