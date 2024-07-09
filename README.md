# Retina Damage Detection from OCT Images with CNN

This project aims to detect retina damage from optical coherence tomography (OCT) images using deep learning techniques. Three different models were employed:

- **Custom CNN Model**:
  - User-designed model architecture tailored for OCT image classification.

- **InceptionV3 Model**:
  - Pre-trained InceptionV3 architecture used for feature extraction and classification.

- **Tuned InceptionV3 Model**:
  - InceptionV3 model fine-tuned on the specific OCT image dataset for optimized performance.

## Model Performance

### Validation Data Results

| Model               | Precision | Recall | F1-Score | Support |
|---------------------|-----------|--------|----------|---------|
| Tuned InceptionV3   | 1.00      | 1.00   | 1.00     | 968     |

### Overall Performance Metrics

- **Accuracy**: 1.00
- **Macro Average Precision**: 1.00
- **Macro Average Recall**: 1.00
- **Macro Average F1-Score**: 1.00
- **Weighted Average Precision**: 1.00
- **Weighted Average Recall**: 1.00
- **Weighted Average F1-Score**: 1.00

## Project Description

This project involved the development and comparison of multiple models for retina damage detection from OCT images. It covers model architecture design, transfer learning with InceptionV3, and fine-tuning techniques applied to improve model accuracy.

## Technologies and Methods Used

- Python, TensorFlow, Keras
- Custom CNN Architecture
- InceptionV3 Transfer Learning
- Model Tuning and Optimization
- Data Preprocessing and Visual Data Analysis
