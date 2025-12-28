# Plant Disease Classification using Convolutional Neural Networks (CNN)

## 📌 Overview
This project implements a **deep learning–based image classification system** to detect and classify **plant diseases from leaf images** using **Convolutional Neural Networks (CNNs)**.  
The goal is to enable **early and automated detection of plant diseases**, which can help reduce crop losses and support precision agriculture.

The model learns discriminative visual features directly from raw image data, eliminating the need for manual feature extraction.

---

## 📂 Dataset
- The dataset consists of **leaf images of healthy and diseased plants**.
- Each image belongs to a specific plant disease category or a healthy class.
- Images are labeled and organized into class-wise directories.

### Preprocessing steps:
- Image resizing to a fixed input shape
- Pixel value normalization
- Dataset splitting into training and validation sets

---

## 🧠 Methodology

### 1. Data Preprocessing
- Loaded image data using directory-based generators
- Applied resizing and normalization
- Prepared training and validation pipelines

### 2. Model Architecture
- Convolutional Neural Network (CNN) consisting of:
  - Convolutional layers for feature extraction
  - Pooling layers for spatial reduction
  - Fully connected (dense) layers for classification
- Activation functions such as ReLU and Softmax used

### 3. Training
- Model trained on labeled plant leaf images
- Loss function: Categorical Cross-Entropy
- Optimizer: Adam
- Performance monitored using accuracy and loss metrics

### 4. Evaluation
- Evaluated using validation accuracy and loss
- Training history visualized to analyze convergence and overfitting

---

## 📊 Results
- The CNN successfully learned visual patterns associated with different plant diseases
- Achieved reliable classification performance on validation data
- Accuracy and loss curves indicate effective learning behavior

*(Exact metrics depend on dataset size and training configuration)*

---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📁 Project Structure
