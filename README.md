# CT Scan Image Classification

This repository contains the code and resources for the CT Scan Image Classification Project. The project focuses on building a Convolutional Neural Network (CNN) model to diagnose Covid-19 from CT scan images.

## Introduction

The **CT Scan Image Classification** is centered around utilizing advanced deep learning techniques to diagnose COVID-19 infections through the analysis of CT scan images. The primary objective of this project is to provide a reliable, efficient, and accurate tool to assist medical professionals in diagnosing COVID-19 cases, particularly in scenarios where traditional testing may be limited.

## Dataset

The [dataset](Data) utilized in this project consists of 2482 CT scan images collected from hospitals in Sao Paulo, Brazil. Among these, 1252 images originate from patients infected with SARS-CoV-2 (COVID-19), while the remaining 1230 images pertain to non-infected patients with other pulmonary diseases. The dataset's diversity ensures a robust training and thorough evaluation of the deep learning model developed.

## How to Run on Google Colab



https://github.com/Pramod858/CT-Scan-Image-Classification/assets/80105491/faf56aa1-d763-40f7-b284-3c09f70e2619



1. Open the Google Colab notebook ['CT_Scan_Image_Classification.ipynb'](Notebook/CT_Scan_Image_Classification.ipynb) by clicking on the provided link:
   [Open in Colab](https://colab.research.google.com/github/Pramod858/CT-Scan-Image-Classification/blob/main/Notebook/CT_Scan_Image_Classification.ipynb)

2. Follow the instructions in the notebook to load the data, preprocess it, construct and train the CNN model, and assess the model's performance.

3. To achieve optimal performance, ensure the Colab runtime is set to use GPU acceleration:
   - Go to 'Runtime' > 'Change runtime type'.
   - Choose 'GPU' under 'Hardware accelerator'.
   - Click 'Save'.

## 📖Note

Given that this project demands GPU acceleration, it is highly recommended to execute it on Google Colab for superior performance.

## Model Performance Metrics

The following table showcases the performance metrics of the trained models:

| Model           | Accuracy | Precision | Recall  | F1 Score | ROC AUC Score |
|-----------------|----------|-----------|---------|----------|---------------|
| Initial Model   | 0.928859 | 0.927027  | 0.929539| 0.928281 | 0.976287      |
| Fine-Tuned Model| 0.973154 | 0.986072  | 0.959350| 0.972527 | 0.998032      |

These metrics provide insights into the effectiveness of the models in diagnosing COVID-19 cases from CT scan images.

## Extra 
Here is the [link](https://drive.google.com/drive/folders/1IoqB6hyF-Kf-nDxw55jcfTEpZhF12rkW?usp=sharing) of `Saved Model` and `Saved Plots`

## Solution Links

1. Solution Code [link](Notebook/CT_Scan_Image_Classification.ipynb)
2. A pdf file which is a document containing screenshots of the application [link](PDF/Screenshots.pdf).
3. A pdf file which is a document where you explain how you approached the problem statement [link](https://github.com/Pramod858/CT-Scan-Image-Classification/blob/main/PDF/CT%20Scan%20Image%20Classification%20Problem%20Statement.pdf).   

