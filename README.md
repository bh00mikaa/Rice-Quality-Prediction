# Rice-Quality-Prediction
This project uses deep learning and transfer learning (ResNet50, Xception, VGG16) to classify rice grain images into five categories. Models are evaluated with accuracy, loss, confusion matrices, and ROC-AUC scores, showcasing efficient image classification in agriculture.

# 🍚 Rice Grain Image Classification using Transfer Learning

This project focuses on classifying rice grain images into five categories using deep learning and transfer learning with popular architectures like **ResNet50**, **Xception**, and **VGG16**.

---

## 📌 Project Description

We implemented and compared multiple CNN models with transfer learning on a dataset of rice grain images. The goal is to accurately classify images into one of five rice grain categories:

- Arborio  
- Basmati  
- Ipsala  
- Jasmine  
- Karacadag  

The project includes model training, evaluation with accuracy/loss curves, confusion matrices, ROC-AUC curves, and final performance reporting.

---

## 📊 Models Used

- **ResNet50**
- **Xception**
- **VGG16**

---

## 📂 Dataset

The dataset consists of images of rice grains categorized into 5 classes. Images were resized to suitable dimensions for each pre-trained model:

- ResNet50: `(50, 50, 3)`  
- Xception & VGG16: `(71, 71, 3)`

---

## 🛠️ Dependencies

- Python 3.x  
- TensorFlow / Keras  
- Scikit-learn  
- Matplotlib  
- Pandas  
- Numpy  

Install them via:

```bash
pip install -r requirements.txt
