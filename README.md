## Agri-Crop quality detection using Deep Learning Algorithms
The project focuses on detecting plant leaf quality using image processing and machine learning. It employs Convolutional Neural Networks (CNNs) for classification, comparing healthy and diseased leaves to identify infections. The system processes high-resolution images, extracts features, and classifies diseases to help farmers apply the right treatments.

## About
The project focuses on identifying plant leaf qulaity and diseases using image processing and machine learning. It utilizes Convolutional Neural Networks (CNNs) for classification, comparing healthy and diseased leaves to detect infections early. The system processes high-resolution images, extracts features, and classifies diseases, enabling farmers to apply the correct pesticide. To enhance accuracy, a Genetic Algorithm (GA) is used for optimization. The dataset is sourced from Kaggle, and additional techniques like SVM and K-Means clustering are explored. This project aims to automate disease detection, reduce manual inspection, and improve agricultural productivity through technology-driven solutions.

## Features
The project utilizes the following key features:

Image Acquisition – Captures high-resolution images of plant leaves.
Image Preprocessing – Enhances image quality by resizing, noise removal, and color correction.
Segmentation – Isolates diseased areas using techniques like K-Means clustering.
Feature Extraction – Extracts texture, color, and shape features from leaf images.
Classification Mechanisms – Uses CNN, SVM, and ANN for disease identification.
Optimization – Implements Genetic Algorithm (GA) for improving model accuracy.
Dataset Utilization – Uses labeled plant leaf images from Kaggle for training.
Performance Metrics – Evaluates accuracy, precision, recall, and F1-score.

## Requirements
### 1. Hardware Requirements:
Processor: Intel i5/i7 or AMD Ryzen 5/7 (or higher)
RAM: Minimum 8GB (Recommended 16GB for better performance)
GPU: NVIDIA GTX 1050 or higher (for faster deep learning computations)
Storage: At least 50GB free space for datasets and model training
### 2. Software Requirements:
Operating System: Windows 10/11, Linux (Ubuntu), or macOS
Programming Language: Python (latest stable version)
IDE/Editor: Jupyter Notebook, Google Colab, VS Code, or PyCharm
### 3. Libraries & Frameworks:
Deep Learning & Machine Learning: TensorFlow, Keras, PyTorch
Image Processing: OpenCV, PIL (Pillow)
Data Handling: NumPy, Pandas
Visualization: Matplotlib, Seaborn
Optimization: Scikit-learn, Genetic Algorithm libraries
### 4. Dataset Requirements:
Source: Kaggle (Corn/Maize Leaf Disease Dataset)
Formats: JPEG, PNG images
Preprocessing: Resizing, Normalization, Augmentation

## System Architecture
The system architecture consists of multiple stages, ensuring an efficient model using deep learning and image processing.

### 1. Image Acquisition Layer
Captures high-resolution plant leaf images using cameras, smartphones, or UAVs (drones).
Images are stored in a local/cloud database for further processing.
### 2. Preprocessing Layer
Noise Removal – Enhances image quality.
Resizing & Normalization – Ensures uniform image dimensions.
Segmentation – Extracts the leaf area using K-Means clustering.
### 3. Feature Extraction Layer
Extracts texture, color, and shape features from leaf images.
Uses CNN feature maps for deep learning-based analysis.
### 4. Classification & Detection Layer
Deep Learning Models (CNN, SVM, ANN) classify healthy and diseased leaves.
Genetic Algorithm (GA) optimizes model performance.
### 5. Output & Decision Layer
Displays results (disease type, severity, and suggested actions).
Sends alerts or recommendations to farmers for corrective actions.


## Output
### Accuracy and losses
![image](https://github.com/user-attachments/assets/b9f46cd4-5b89-41bf-994a-d337d8d65d4a)

### Genetic Algorithm
![image](https://github.com/user-attachments/assets/8d5b55d1-91c1-470b-9bc8-209487529d85)

![image](https://github.com/user-attachments/assets/a74b4559-9fd5-4b56-ac67-dc2ce3921a6a)


![WhatsApp Image 2025-03-07 at 23 49 03_d7d96df2](https://github.com/user-attachments/assets/3a696e75-cd47-4ca6-b998-68e788d4ef2d)

## Results and Impact

The implementation of this project has a significant impact on modern agriculture by enhancing crop monitoring, reducing losses, and promoting sustainable farming practices. By enabling early disease detection, farmers can take timely action, preventing large-scale crop damage and improving overall agricultural productivity. The system also reduces the excessive use of pesticides, as it helps in identifying specific diseases, allowing targeted treatment rather than broad-spectrum chemical application. Furthermore, this AI-driven approach supports precision agriculture, where machine learning and IoT-based monitoring can be integrated for real-time field analysis. Ultimately, the project contributes to cost-effective, data-driven, and environmentally friendly farming solutions, making it a valuable tool for the future of agriculture.

## Articles published / References
1. Muhammad Suleman Memon ,ORCID,Pardeep Kumar Pardeep Kumar SciProfilesScilitPreprints.orgGoogle Scholar ORCID andRizwan Iqbal 3 https://www.mdpi.com/1689818
2. Faiza Khan, Noureen Zafar, Muhammad Naveed Tahir, Muhammad Aqib, Hamna Waheed, Zainab Haroon
https://doi.org/10.3389/fpls.2023.1079366
3. Sachin Jadhav, Dr. Vishwanath Udupi,Dr. Sanjay Patil
4. Amreen Abbas, Sweta Jain, Mahesh Gour, Swetha Vankudothu https://doi.org/10.1016/j.compag.2021.106279
5. André Abade, Paulo Afonso Ferreira, Flavio de Barros Vidal https://doi.org/10.1016/j.compag.2021.106125
6. Gianni Fenu, Francesca Maridina Malloci https://www.mdpi.com/957380
7. Amanda Ramcharan, Peter McCloskey, Kelsee Baranowski, https://doi.org/10.3389/fpls.2017.01852
8. Xuewei Wang, Jun Liu, Guoxu Liu https://doi.org/10.3389/fpls.2021.792244
9. Rehan Ullah Khan,Khalil Khan,Waleed Albattah https://doi.org/10.1155/2021/5541859
10. Lakshay Goyal, Chandra Mani Sharma, Anupam Singh, Pradeep Kumar Singh
https://doi.org/10.1016/j.imu.2021.100642




