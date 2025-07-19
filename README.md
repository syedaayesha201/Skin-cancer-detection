# Skin Cancer Detection Using Deep Learning on Dermoscopic Images

This project focuses on detecting **skin cancer** using image classification techniques with deep learning models. It involves preprocessing dermoscopic images by converting them to grayscale, extracting key features, and training a CNN-based model to classify lesions accurately.

---

## 🧾 Project Overview

Skin cancer is one of the most common forms of cancer, and early detection plays a critical role in treatment success. This project applies computer vision and deep learning techniques to classify skin lesions from dermoscopic images as either cancerous or non-cancerous.

---

## 🖼️ Dataset Description

- **Image Type**: Dermoscopic RGB images
- **Preprocessing**: All 3D RGB images were converted to **grayscale** to reduce complexity and computational load.
- **Image Resizing**: Standardized input size for consistent CNN performance.
- **Labels**: Binary classification — Malignant or Benign

---

## 🧠 Techniques Used

- **Image Preprocessing**:  
  - RGB to Grayscale conversion  
  - Resizing and normalization  
- **Model Architecture**:  
  - Convolutional Neural Network (CNN)  
  - Layers: Conv2D, MaxPooling, Flatten, Dense, Dropout  
- **Loss Function**: Binary Crossentropy  
- **Optimizer**: Adam  
- **Activation**: ReLU (hidden layers), Sigmoid (output layer)

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**
- **Model Loss vs Accuracy Graphs**

---

## 🔧 Tools & Technologies

- **Language**: Python  
- **Libraries**:
  - TensorFlow / Keras
  - NumPy
  - Matplotlib
  - OpenCV
- **Platform**: Google Colab

---

## 🚀 How to Run the Project

1. Clone the repository or upload the notebook to Google Colab.
2. Upload the image dataset to your Colab environment.
3. Run all notebook cells in order:
   - Preprocessing  
   - Model building  
   - Training  
   - Evaluation

---

## 📁 Folder Structure

```bash
SkinCancerDetection/
│
├── skin_cancer_detection.ipynb      # Main project notebook
├── images/                          # Folder containing image dataset
├── README.md                        # Project documentation
└── model_results/                   # Folder for saved metrics/graphs
