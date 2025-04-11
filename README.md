# 🌾 Rice Leaf Disease Detection

An end-to-end deep learning project for detecting rice leaf diseases using Convolutional Neural Networks.

## 🧠 Model Information
- Multiple models trained on a rice leaf image dataset (3 classes):
  - Custom CNN
  - CNN with Data Augmentation
  - InceptionV3 (with and without augmentation)
  - Xception (with and without augmentation)
- **Best Accuracy**: 83.33% using **InceptionV3 with Data Augmentation**
- Final model saved as `rice_leaf_model.keras` for deployment
  
## 💻 Tech Stack
- Python, TensorFlow, Keras, Streamlit, Google Colab
  
## 📁 Files in This Project
-main.py – Streamlit app for model inference
-class_indices.json – Mapping of class indices to disease names
-rice_leaf_model.keras – Trained model ready for deployment
-RICE_LEAF_DISEASES_DETECTION_.ipynb – Notebook for training and evaluation

## 🖼️ Classes Detected
- Bacterial leaf blight
- Brown spot
- Leaf smut
