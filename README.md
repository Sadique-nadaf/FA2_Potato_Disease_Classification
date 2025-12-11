
# FA2 — Potato Disease Classification (Deep Learning)

**Student:** Sadique Chand Nadaf  
**PRN:** 125M1K014  

## Project Overview

This project implements **Potato Leaf Disease Classification** using **Deep Learning (CNNs)** with two Transfer Learning models:

1. **MobileNetV2**
2. **ResNet50**

The goal is to classify potato leaf images into **3 classes**:
- Early Blight
- Healthy
- Late Blight

---

## 📁 Repository Structure
```
FA2_Potato_Disease_Classification/
│
├── notebooks/
│   ├── FA2_Deep_Learning_MobileNetV2.ipynb
│   ├── FA2_Deep_Learning_ResNet50.ipynb
│
├── models/
│   ├── MobileNetV2_FA2.txt
│   ├── ResNet50_FA2.txt
│
├── outputs/
│   ├── MobileNet_accuracy_loss_plot.png
│   ├── MobileNet_confusion_matrix.png
│   ├── MobileNet_classification_report.txt
│
│   ├── ResNet50_accuracy_loss_curve.png
│   ├── ResNet50_confusion_matrix.png
│   ├── ResNet50_classification_report.txt
│
├── README.md
└── (Dataset not included due to size)
```

---

## Dataset


**Dataset Used:** `PLD_3_Classes_256`  
Contains 3 folders:
- `Training/`
- `Validation/`
- `Testing/`

Each class has sufficient images to train deep models.

**Dataset Source:** (https://www.kaggle.com/datasets/rizwan123456789/potato-disease-leaf-datasetpld).

---

##  Models Implemented

### 1. MobileNetV2
- Lightweight CNN model
- Fast training
- Achieved **95%+ Test Accuracy**
- Best for mobile/edge deployment

### 2. ResNet50
- Deep and powerful CNN
- Slower training (6–12 minutes per epoch)
- Achieved **96%+ Test Accuracy**
- More stable feature extraction

---

## 📊 Model Performance

### MobileNetV2
- **Test Accuracy:** ~0.95
- Plots & reports available in `/outputs/`

**Files:**
- `MobileNet_accuracy_loss_plot.png`
- `MobileNet_confusion_matrix.png`
- `MobileNet_classification_report.txt`

### ResNet50
- **Test Accuracy:** ~0.967
- Outperformed MobileNetV2

**Files:**
- `ResNet50_accuracy_loss_curve.png`
- `ResNet50_confusion_matrix.png`
- `ResNet50_classification_report.txt`

---
