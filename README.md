# 📌 Carotid Artery Segmentation using U-Net

A deep learning-based approach for segmenting carotid arteries from ultrasound images using the U-Net architecture.  
This project demonstrates the application of semantic segmentation in medical imaging to aid in vascular health assessment.

---

## 🧠 Model Architecture

This project utilizes the **U-Net** architecture, a widely used convolutional network for biomedical image segmentation.

- **Encoder**: Convolution → ReLU → MaxPooling  
- **Decoder**: Transposed Convolution → Concatenation with Encoder Output (Skip Connections)  
- **Loss Function**: Dice Loss + Binary Cross Entropy (BCE)

---

## 🗃️ Dataset

- **Source**: [Carotid Artery Ultrasound Images Dataset – Kaggle](https://www.kaggle.com/datasets/naveengowtham/carotid-artery-ultrasound-images)
- **Description**: Paired ultrasound images and manually annotated segmentation masks for carotid arteries.
- **Preprocessing**: All images and masks were resized to **256×256** for training consistency and efficiency.

---
