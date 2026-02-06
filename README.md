# Plant Disease Detection System 🍃

![Python](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Validation%20Accuracy-98.22%25-success?style=for-the-badge)

## 📌 Project Overview
Agriculture faces significant threats from crop diseases, which reduce global yields by up to 40%. This project is an **AI-powered prototype** designed to automate the early detection of plant diseases using deep learning.

Trained on open source Kaggle **PlantVillage dataset**, our custom Convolutional Neural Network (CNN) classifies leaf pathologies with **98.22% accuracy**, providing a scalable, cost-effective tool for farmers to identify crop health issues instantly.

## 🚀 Key Features
* **Custom CNN Architecture:** Engineered a 4-block deep learning model:
    * **4 Convolutional Blocks:** Filters increasing from 32 to 256.
    * **Regularization:** Batch Normalization and Dropout layers (0.3 - 0.5) to prevent overfitting.
    * **Classification Head:** Global Average Pooling + Dense Layers (512 & 256 neurons).
* **Robust Data Pipeline:**
    * **Preprocessing:** Resizing (224x224), Normalization (1./255).
    * **Augmentation:** Applied to enhance model generalization.
* **High Performance:** Achieved convergence within 50 epochs with minimal loss variance.

## 📊 Model Performance
The model was evaluated over **50 epochs** on a validation split of 20%.

| Metric | Result |
| :--- | :--- |
| **Training Accuracy** | **98.24%** |
| **Validation Accuracy** | **98.22%** |
| **Loss Function** | Categorical Cross-Entropy |
| **Optimizer** | Adam |

## 🛠️ Tech Stack
* **Core:** Python 3.x
* **Deep Learning:** TensorFlow, Keras
* **Data Processing:** NumPy, Pandas, Pillow (PIL)
* **Visualization:** Matplotlib (Accuracy/Loss Curves)

## 📂 Visuals
### 1. Training Performance
![Accuracy Graph](INSERT_GRAPH_LINK_HERE)
*Figure 1: Training vs. Validation Accuracy over 50 epochs, showing stable convergence.*

### 2. Disease Prediction
![Prediction Sample](INSERT_LEAF_LINK_HERE)
*Figure 2: Model successfully classifying a leaf pathology from the test set.*

## 🔮 Future Work: "Plant Talking" 🌱
The next phase involves integrating **IoT Biocommunication**:
* **Concept:** Enabling plants to "communicate" physiological needs (water stress, nutrient deficiency) via sensors.
* **Implementation:** A network of soil moisture, temperature, and light sensors will feed data into this central AI system.
* **Goal:** A fully autonomous "Smart Irrigation Solution" that responds to plant signals in real-time.

## 🤝 Contributors
* **Shaurya Jain** - *Model Architecture & Training*
* **Vanshita Surana** - *Data Analysis & Documentation*
