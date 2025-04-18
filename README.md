# 🍇 Grapevine Leaf Classification using CNN and Transfer Learning

## Overview

This project classifies grapevine leaves into 5 categories: `Ak`, `Ala_Idris`, `Buzgulu`, `Dimnit`, and `Nazil` using various deep learning models:

- **Custom CNN**
- **Transfer Learning with MobileNet and ResNet**
- **Feature Extraction using ResNet + SVM**

## Dataset

- The dataset contains labeled images of grapevine leaves belonging to 5 classes.
- Each image is resized to 224x224 for model input.
- Dataset source: (https://www.kaggle.com/datasets/muratkokludataset/grapevine-leaves-image-dataset)

## Models Tried

| Model                             | Accuracy (%) |
|-----------------------------------|--------------|
| Custom CNN                        | 27           |
| MobileNet (Transfer Learning)     | 31           |
| ResNet50 (Transfer Learning)      | 94.4         |
| ResNet50 Features + SVM           | 96.8         |

##  Technologies Used

- **PyTorch** for deep learning
- **Torchvision** for pretrained models
- **Scikit-learn** for SVM and evaluation

## Training Setup

- **Optimizer**: Adam
- **Loss Function**: CrossEntropyLoss
- **Image Size**: 224x224
- **Epochs**: 5 (adjustable)

## Evaluation

- **Metrics used**: Accuracy, Classification Report
- **Best result achieved** with ResNet + SVM: **96.8% accuracy**
