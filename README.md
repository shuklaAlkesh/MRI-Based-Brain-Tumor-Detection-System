# 🧠 MRI-Based Brain Tumor Detection System

This project leverages **Deep Learning** and **Image Processing** techniques to classify brain tumors from MRI images. By using models like **Convolutional Neural Networks (CNN)** and **Support Vector Machines (SVM)**, as well as advanced techniques such as **Wavelet Transformation** and **MobileNetV2**, this system aims to provide an accurate and efficient solution for brain tumor classification.

<img align="right" alt="Brain Tumor Detection" height="300" width="400" src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*_pCEmeOrVkayCFER33o4Cw.jpeg">

## 📋 Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Setup](#setup)
- [License](#license)

## 💡 Introduction
Brain tumors are a critical health concern that affects thousands of lives globally. Identifying whether a brain tumor is **benign** or **malignant** is crucial for determining treatment options. This project provides an automated solution for detecting and classifying brain tumors using **MRI image analysis**.

## 🚀 Technologies Used
- **Deep Learning Models**: CNN, ANN, Logistic Regression, SVM, and MobileNetV2.
- **Wavelet Transformation**: Used for feature extraction to capture fine details from the MRI images.
- **Data Augmentation**: Involves rotation, brightness adjustment, and horizontal flipping of images to create a robust training set.

## 🔧 Methodology
1. **Data Preprocessing**: Images are rescaled and normalized using TensorFlow's `ImageDataGenerator`. Pixel values are divided by 255, and additional transformations (rotation, brightness) are applied.
2. **Data Augmentation**: Helps in preventing overfitting and ensures that the model generalizes well to unseen data.
3. **Feature Extraction**: Wavelet transformation is applied to extract essential features from the MRI images.
4. **Model Training**:
   - **CNN**: Used to capture spatial hierarchies in the MRI data.
   - **SVM**: A classical machine learning approach that works well for high-dimensional data.
   - **Logistic Regression**: A simpler, interpretable model that serves as a baseline.
   - **MobileNetV2**: A pre-trained model fine-tuned for brain tumor detection, providing a balance between performance and computational efficiency.
5. **Visualization**: Pie charts and bar graphs visualize data distribution across different tumor classes.

## 📊 Results
The model achieved the following accuracy rates on the testing data:
- **Artificial Neural Network (ANN)**: 31.64%
- **Convolutional Neural Networks (CNN)**: 87.5%
- **Support Vector Machines (SVM)**: 87.4%
- **Logistic Regression**: 82.85%
- **ANN + MobileNetV2**: 🏆 **90.2%**

MobileNetV2, combined with ANN, achieved the highest accuracy due to its pre-trained weights and efficient feature extraction capabilities.

## 📚 Conclusion
This project demonstrates the potential of **AI in healthcare** by showing how **deep learning** and **pre-trained models** can enhance medical diagnostics. The use of **MobileNetV2** significantly boosted accuracy, proving the importance of transfer learning in medical image analysis.

Continued innovation in AI models will play a key role in improving diagnostic accuracy and supporting medical professionals in their decision-making processes.

## 🛠 Setup
To get started with this project, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/shuklaAlkesh/MRI-Based-Brain-Tumor-Detection-System.git
