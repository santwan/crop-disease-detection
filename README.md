# 🌾 Crop Disease Prediction using EfficientNet-B3

A deep learning-based web solution to identify plant leaf diseases from images using a fine-tuned EfficientNet-B3 model. Built for farmers and agriculture enthusiasts to improve crop health and yield through early disease detection.

---

## 📌 Project Overview

- **Name**: AI-Driven Crop Disease Prediction System
- **Objective**: Classify plant leaf images to detect diseases and suggest remedies.
- **Model Type**: Fine-tuned EfficientNet-B3 (Pre-trained on ImageNet)
- **Framework**: PyTorch
- **Interface**: Web app (to be integrated)

---

## 🧠 Model Features

- **Input**: Leaf image (Resized to 300x300)
- **Output**: Predicted disease class with confidence score
- **Classes**: 38 crop disease categories from the PlantVillage dataset
- **Accuracy**: 93.23% on validation set
- **Inference**: Fast and lightweight model for deployment

---

## 📂 Dataset Info

- **Source**: [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Total Images**: ~41,276
  - **Training**: 33,020 images
  - **Validation**: 8,256 images
- **Format**: Images grouped in folders per class

---

## ⚙️ Training Configuration

| Parameter         | Value               |
|------------------|---------------------|
| Model             | EfficientNet-B3     |
| Optimizer         | Adam                |
| Learning Rate     | 1e-4                |
| Epochs            | 5                   |
| Batch Size        | 32                  |
| Loss Function     | CrossEntropyLoss    |
| Hardware Used     | Intel i5 11th Gen CPU (No GPU) |
| Training Time     | ~X hours            |

---

## 📊 Performance Metrics

- **Training Accuracy**: 87.33%
- **Validation Accuracy**: 93.23%
- *(Add your training/validation loss plot or confusion matrix here if available)*

---

## 🛠️ How to Use

### 🔧 Setup

```bash
git clone https://github.com/your-username/crop-disease-prediction.git
cd crop-disease-prediction
pip install -r requirements.txt
