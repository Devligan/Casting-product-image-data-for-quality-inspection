# 🛠️ Automated Casting Defect Detection using Deep Learning

## Overview

Manual inspection of metal castings in manufacturing is **expensive**, **slow**, and **inconsistent**. Trained inspectors must evaluate thousands of parts daily, yet human error and fatigue often lead to missed defects — putting safety, cost, and quality at risk.

This project uses **deep learning and computer vision** to automate the detection of casting defects from industrial images. By training a convolutional neural network (CNN) on labeled casting images, the model classifies each part as either **Defective** or **Normal**, reducing the need for manual checks and enabling scalable quality control.

## 🔍 Dataset

- **Source**: [Kaggle - Industrial Casting Dataset](https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product)
- **Classes**:
  - `0` → Defective
  - `1` → Normal
- Images are grayscale photographs of side-casting components.

## 🚀 Project Highlights

- ✅ Preprocessing pipeline with image augmentation
- ✅ Fine-tuned **ResNet18** model using transfer learning
- ✅ Evaluation with **accuracy, precision, recall, ROC AUC**, and **confusion matrix**
- ✅ Explainability via **SHAP** to interpret model predictions
- ✅ Visual overlays to show model reasoning on individual images
