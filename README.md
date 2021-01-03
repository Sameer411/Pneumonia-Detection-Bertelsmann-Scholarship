# Pneumonia-Detection-Bertelsmann-Scholarship
Worked on the Project Pneumonia Detection using Chest X Ray in the Phase 1 Period of Bertelsmann Nano Degree Scholarship Program

The purpose of this project is to examine a Convolution Neural Network model on the image classification problem of Pneumonia Detection in chest X-Ray images. 


The Train Model is having Accuracy of 94% and Validation Accuracy of 85% 


# Methods and Algorithms Used 

1) Image Data Preprocessing
2) Machine Learning
3) Trasfer Learning
4) Image Classification
5) Convolution Neural Network
6) Precision, Recall, F1-Score 


# Technologies
1) Python
2) Keras
3) Scikit-learn
4) NumPy, Pandas
5) Matplotlib, Seaborn
6) Jupyter Notebook


# Dataset
The dataset used in the project is available on [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) it contains  5856 labeled pediatric chest X-ray images, distributed in **three classes**: 
1. normal
2. pneumonia
3. Val 


# Project Description
This project includes implementation of deep learning and computer vision techniques for detection of pneumonia in X-ray images from the Chest X-ray Images dataset. The CNN model classifies whether or not pneumonia shows up on the chest X-ray images, therefore only two predictions are possible, normal or pneumonia.

In the data preprocessing step, samples from the dataset are resized to a shape (64,64), normalized and converted to the RGB color space. To reduce the classification bias caused by data imbalance, class weights are applied.

The classifier used is the VGG-19 model with weights pre-trained on the ImageNet dataset. This network is supported in the Keras library, along with a transfer learning workflow performed in the project. The workflow consists of two phases, the first includes optimizing the output (classification) layer only, while the second includes retraining (fine-tuning) the entire network with much smaller learning rate. The training is performed in 25 epochs in the first phase and one final fine-tuning epoch in the second.

Evaluation of the model is performed with accuracy, precision, recall and f1-score metrics on the validation set. Confusion matrices and other appropriate plots are used to further describe obtained results as well.


# How to Run the Code
1. Go to Provided Dataset Link 
2. Download and Extract the file 
3. Upload the extracted file in your Drive account 
4. Open the google collab ipynb file in Google Colab
5. Run Each Cell and You will get the Output 


Read the Research Paper Before starting the Project. Do Research before Starting the Project 
