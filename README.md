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

## Getting started 
- Download and run the notebook files


