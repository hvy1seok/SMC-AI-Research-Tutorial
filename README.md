![img](https://github.com/user-attachments/assets/d427faa7-7b64-4147-885e-2659b25c75dc)
![SKKU_MARS_v5](https://github.com/user-attachments/assets/0108c3c3-a2b4-425f-8493-6839760fe2ce)
# SMC AI Research: Tutorial Projects

Welcome to the SMC AI Research tutorial projects repository. This repository contains two important projects that are designed to guide new members of our team through the process of building AI models for medical image analysis.

## Projects Overview

### 1. **Pneumonia Classification**

This project focuses on the development of a Convolutional Neural Network (CNN) to classify chest X-ray images for detecting pneumonia. The task involves:

- **Dataset**: Chest X-ray images labeled as either pneumonia or normal.
- **Objective**: Develop a model to classify whether a given chest X-ray shows signs of pneumonia.
- **Tools Used**: 
  - PyTorch for model development.
  - Scikit-learn for performance evaluation metrics.
  - Matplotlib for visualization.
- **Outcome**: A trained model that can accurately classify chest X-rays into normal or pneumonia categories, with metrics like accuracy, AUROC, and AUPRC to evaluate its performance.

### 2. **3D Liver Segmentation**

This project involves the segmentation of liver structures from 3D medical imaging data (such as CT scans). It demonstrates the application of a 3D U-Net architecture for volumetric segmentation tasks. Key aspects include:

- **Dataset**: 3D CT scan volumes with labeled liver regions.
- **Objective**: Develop a segmentation model that can accurately identify and delineate liver structures in 3D images.
- **Tools Used**: 
  - PyTorch for model development.
  - Nibabel for handling NIfTI image files.
  - Matplotlib and Celluloid for visualizing the segmentation results in the form of animated slices.
- **Outcome**: A 3D U-Net model capable of segmenting the liver from CT scans, with the ability to visualize the results slice-by-slice in an animated format.

## Purpose of These Projects

These projects are part of the SMC AI Research tutorial series, specifically designed to help new members get familiar with the tools, techniques, and workflows commonly used in our research. The focus is on understanding the tasks at hand—classification and segmentation of medical images—and learning how to approach these problems with state-of-the-art machine learning models.

Through these tutorials, you will gain hands-on experience in:

- Setting up and preprocessing medical imaging datasets.
- Designing, training, and evaluating deep learning models for classification and segmentation tasks.
- Visualizing results to understand model performance.

We encourage new members to go through these projects, experiment with the code, and get comfortable with the process of developing AI solutions for medical image analysis.

## Getting Started

To get started with these projects:

1. Clone the respective repositories:
   - `1.Pneumonia_Classification`
   - `2.3D-Liver_Segmentation`:
   
2. Follow the instructions in the Jupyter notebooks to understand the workflow and execute the code.
3. Refer to the comments in the code for guidance and feel free to modify and experiment with the models.

## Contributing

These projects are meant to be a learning resource. If you have suggestions or improvements, feel free to fork the repositories, make changes, and submit a pull request(NOT RECOMMENDED).

## Credits

Created by **Wonseok Jang**.
