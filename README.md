# Analysis-of-Transfer-Learning-for-Image-Classification-on-Sparse-Data
- This repository contains the code and findings of a comprehensive analysis of transfer learning for image classification on sparse datasets.

## Research Problem 🔍
- Identifying the key components influencing transfer learning success.
- Choosing the most suitable model for sparse data scenarios.
- Addressing the limitations of previous works regarding diversity and generalizability.

## Overview 📝
- Conducted a thorough analysis using four pretrained models (MobileNetV2, MobileNetV3Large, EfficientNetB0, and EfficientNetB5).
- Applied transfer learning to two diverse datasets: skin disease classification (multiclass) and waste classification (binary).
- Explored four transfer learning approaches: feature extractor + classifier, fine-tuning entire network, and their combinations with data augmentation.

## Results 📊
- Implemented data augmentation, resulting in a substantial boost in test accuracy (1.6% to 11.8% increase).
- Identified the crucial role of feature extraction in the success of transfer learning.
- Found that the combination of fine-tuning and data augmentation is effective, especially in limited data scenarios.
- Lightweight models outperformed largescale models in fine-tuning + data augmentation with limited data.

## Accuracy Calculation in Binary and Multiclass Classification
#### Binary Classification

In binary classification, accuracy is calculated using True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN). The formula for accuracy in binary classification is: Accuracy = (TP + TN) / (TP + TN + FP + FN)

Where:
- TP: True Positives
- TN: True Negatives
- FP: False Positives
- FN: False Negatives

This formula represents the ratio of correctly classified instances (both positive and negative) to the total number of instances.

#### Multiclass Classification

In multiclass classification, accuracy is calculated differently. You sum up the True Positives (TP) for each class and then divide by the total number of samples. The formula for accuracy in multiclass classification is: Accuracy = Total True Positives / Total Number of Samples

Where:
- Total True Positives: The sum of the true positives for each class.
- Total Number of Samples: The total number of samples across all classes.

Referred from - [Accuracy, precision, and recall in multi-class classification]([https://github.com/hanzhanggit/StackGAN](https://www.evidentlyai.com/classification-metrics/multi-class-metrics#:~:text=However%2C%20to%20calculate%20accuracy%2C%20we,%E2%80%9Cblind%E2%80%9D%20to%20specific%20classes.&text=To%20calculate%20accuracy%2C%20divide%20all,37%2F45%20%3D%2082%25.)https://www.evidentlyai.com/classification-metrics/multi-class-metrics#:~:text=However%2C%20to%20calculate%20accuracy%2C%20we,%E2%80%9Cblind%E2%80%9D%20to%20specific%20classes.&text=To%20calculate%20accuracy%2C%20divide%20all,37%2F45%20%3D%2082%25.)

## Getting started 
- Download and run the notebook files


