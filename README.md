 Satelliet Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) to classify satellite images into different land use categories using the EuroSAT dataset. The model achieves high accuracy in predicting classes like residential, industrial, river, forest, and more based on satellite imagery.

## 🚀 Project Overview

- **Objective**: Automatically classify satellite images into predefined land use categories.
- **Dataset**: EuroSAT RGB dataset (Sentinel-2 satellite images) containing 27,000 labeled images across 10 classes.
- **Model**: A custom-built CNN using TensorFlow and Keras with multiple convolutional, pooling, and dense layers.
- **Accuracy Achieved**: **91.92%** on the validation set.

## 🧠 Key Features

- Image preprocessing and augmentation using Keras `ImageDataGenerator`.
- CNN model with dropout layers to prevent overfitting.
- Evaluation using confusion matrix and per-class prediction visualizations.
- Easily reproducible and modifiable pipeline.

## 📁 Project Structure

├── 0_build_rgb_dataset.ipynb # Dataset preparation
├── 1_preprocess_dataset.ipynb # Image preprocessing and resizing
├── 2_cnn_model.ipynb # CNN model building and training
├── README.md # Project overview and details


## 🔍 Sample Classes

- Annual Crop  
- Forest  
- Residential  
- River  
- Sea/Lake  
- Highway  
- Industrial  
- Pasture  
- Permanent Crop  
- Herbaceous Vegetation

## 🧑‍💻 My Role

- Designed and implemented the full CNN model architecture.
- Handled data preprocessing and image augmentation.
- Visualized performance using confusion matrices and matplotlib plots.
- Tuned hyperparameters and improved generalization with dropout layers.

## 🛠️ Tech Stack

- Python  
- TensorFlow/Keras  
- NumPy  
- Matplotlib  
- Seaborn

## 📊 Results

- **Training Accuracy**: 97.62%  
- **Validation Accuracy**: **91.92%**



📎 References

    EuroSAT Dataset on Kaggle
