# 🧠 Brain Tumor Classification

This project implements an **image classification model** for brain tumor detection using deep learning. The model is trained on augmented MRI scan images and classifies them into four categories:

- **Glioma**
- **Meningioma**
- **Pituitary**
- **Healthy**

The project includes:
- Data preprocessing and augmentation
- Hyperparameter optimization with Keras Tuner
- Model training with early stopping
- Final evaluation and sample visualizations

---
### 🔍 Best Hyperparameters (Selected via Keras Tuner)

- Activation Function: `relu`
- Number of Convolutional Layers: `3`
- Filters per Layer:
  - Layer 1: `128 filters`
  - Layer 2: `64 filters`
  - Layer 3: `32 filters`
- Dense Layer Units: `96`
- Dropout Rate: `0.2`
- Learning Rate: `0.0001`


---
## 📊 Evaluation Metrics

![image](https://github.com/user-attachments/assets/a73c5e8a-92a2-43af-bf61-6ec92cb97088)

---

📎 **Project Files (Notebook + Model + Resources)**  
[📂 Access via Google Drive](https://drive.google.com/drive/folders/1HuAeoD_YLON65MNzkGnfXgFXfoWmS3Eq?usp=sharing)





