# 🧠 Brain Tumor Detection Using Deep Learning Techniques

This project focuses on the **automated detection of brain tumors from MRI images** using various deep learning models. It evaluates multiple architectures to determine the most accurate and efficient model for binary classification of brain tumor presence.


## 📌 Overview

Implemented and compared the following models:
- **VGG-19**
- **ResNet**
- **K-Nearest Neighbors (KNN)**
- **Kolmogorov-Arnold Networks (KAN)**
- **Deep Belief Network (DBN)**


## 🧩 Dataset

The dataset contains **253 Brain MRI images**:

- 🧠 `Yes/` — 155 images with diagnosed brain tumors  
- 🧠 `No/` — 98 healthy MRI images

This dataset supports **binary classification** based on MRI image inputs.


## 📊 Model Accuracy Summary

| Model     | Training Accuracy (%) | Validation Accuracy (%) | Test Accuracy (%) |
|-----------|------------------------|--------------------------|--------------------|
| VGG-19    | 94.80                  | 81.48                    | **94.44**          |
| ResNet    | 78.00                  | 74.07                    | 75.93              |
| KNN       | 84.40                  | 77.78                    | 79.63              |
| KAN       | 88.80                  | 77.78                    | 88.89              |
| DBN       | 78.40                  | 75.93                    | 79.63              |


## 📁 Files in This Repository

- `code1-KAN.ipynb` – Kolmogorov-Arnold Networks (KAN)
- `code2-VGG19.ipynb` – VGG-19 Model
- `code3-KNN.ipynb` – K-Nearest Neighbors
- `code4-RESNET.ipynb` – ResNet Model
- `code5-DBN.ipynb` – Deep Belief Network


## ✅ Results & Observations

- **VGG-19** outperformed all models with **94.44% test accuracy**, showcasing strong generalization and feature extraction.
- **KAN** achieved **88.89% test accuracy**, proving effective and stable.
- **KNN** and **DBN** showed moderate accuracy (~79%), with some limitations in generalization.
- **ResNet** performed the lowest, potentially due to underfitting or lack of fine-tuning.


## 🚀 Future Improvements

- **Hyperparameter Tuning**: Grid Search or Bayesian Optimization
- **Data Augmentation**: Enhance dataset diversity and robustness
- **Advanced Architectures**: Try EfficientNet, Vision Transformers (ViT), Swin Transformers
- **Transfer Learning Enhancements**: Fine-tune more layers for better generalization


## 📢 Conclusion

This project showcases the potential of deep learning models in **medical imaging**. Among all, **VGG-19** emerged as the best performer. With enhancements in architecture and training techniques, such systems could aid real-world diagnostic tools.



