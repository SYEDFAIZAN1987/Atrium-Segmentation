# 🫀 Atrium Segmentation Project using U-Net

Welcome to the **Atrium Segmentation Project**, where we leverage deep learning techniques, specifically the **U-Net architecture**, to perform precise segmentation of the atrium from cardiac MRI scans. This project is designed to assist in medical imaging analysis, enhancing diagnostic capabilities for cardiovascular diseases.

---

## 📊 **Project Overview**

The goal of this project is to accurately segment the left atrium from MRI images, providing clear boundaries for better clinical assessments. The segmentation is achieved using a robust **U-Net** model, tailored for biomedical image segmentation tasks.

### 🔍 **Key Features:**
- **End-to-End Pipeline**: Data preprocessing, model training, evaluation, and visualization.
- **Advanced Data Augmentation**: Enhances generalization using elastic transformations, rotations, and affine augmentations.
- **High-Quality Results**: Achieves accurate segmentation even on complex cardiac MRI scans.

---

## 🧠 **U-Net Architecture**

The U-Net model is specifically designed for biomedical image segmentation tasks. Its architecture consists of an encoder-decoder structure with skip connections, ensuring the preservation of spatial information.

![U-Net Architecture](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/blob/main/unet.png)

### **Why U-Net?**
- Efficient for small datasets (common in medical imaging).
- Maintains high accuracy through symmetric contracting and expanding paths.
- Excellent for pixel-wise classification tasks like segmentation.

---

## 🚀 **Model Training**

The training process involves feeding preprocessed MRI slices into the U-Net model with corresponding segmentation masks. Data augmentation techniques improve the model's robustness to variations in input data.

![Training Process](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/blob/main/Atrium%20Segmentation%20Training.png)

### **Training Details:**
- **Optimizer:** Adam
- **Loss Function:** Dice Coefficient Loss + Binary Cross-Entropy
- **Epochs:** 50 (adjustable)
- **Batch Size:** 16
- **Learning Rate:** 0.001

---

## 🎥 **Model Evaluation**

After training, the model is evaluated on unseen MRI data to validate its performance. The evaluation includes metrics like **Dice Similarity Coefficient**, **Precision**, and **Recall**.

### **Evaluation Video:**

[![Evaluation Video](https://img.youtube.com/vi/placeholder/0.jpg)](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/blob/main/Atrium%20Segmentation%20Evaluated%20on%20a%20subject.mp4)

---

## 🗂️ **Project Structure**

 
