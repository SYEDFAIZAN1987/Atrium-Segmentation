# 🫀 Atrium Segmentation Project using U-Net
By 
Syed Faizan
Welcome to the **Atrium Segmentation Project**, where we leverage deep learning techniques, specifically the **U-Net architecture**, to perform precise segmentation of the atrium from cardiac MRI scans. This project is designed to assist in medical imaging analysis, enhancing diagnostic capabilities for cardiovascular diseases.

[![Sample Augmentation](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/blob/main/Sample%20Augmentation.png)
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
- **Loss Function:** Dice Coefficient Loss 
- **Epochs:** 75 
- **Batch Size:** 16
- **Learning Rate:** 0.001

---



## 🎥 **Model Evaluation**
Click on the image below to download and watch a sample MRI tested using the model 



[![Click to Watch](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/blob/main/Atrium%20Segmentation%20Training.png)](https://github.com/SYEDFAIZAN1987/Atrium-Segmentation/raw/main/Atrium%20Segmentation%20Evaluated%20on%20a%20subject.mp4)




## 🗂️ **Project Structure**
```
Atrium-Segmentation/ ├── data/ # Raw MRI images and labels ├── Preprocessed/ # Processed images and masks ├── models/ # Trained model weights ├── utils/ # Helper functions for data handling ├── notebooks/ # Jupyter notebooks for EDA and model training ├── Atrium Segmentation Evaluated on a subject.mp4 ├── Atrium Segmentation Training.png ├── unet.png └── README.md # Project documentation
```
## 📈 **Results**

The U-Net model achieves:

- **Dice Similarity Coefficient (DSC):** 0.95

This result demonstrates the model's strong ability to segment atrial structures accurately.

---

## 🤝 **Contributing**

Contributions are welcome! To contribute:
```
1. **Fork** the repository.  
2. **Create a new branch:**
git checkout -b feature-branch 
   ```

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 🙌 Acknowledgments
Special thanks to:

The medical imaging community for datasets and resources.
U-Net developers for the foundational architecture.
nibabel for neuroimaging data processing.

   
   




 
