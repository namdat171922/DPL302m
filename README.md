# DPL302m
🧠 EfficientNet-B7 for Diabetic Retinopathy Classification
📘 Overview
This project implements a deep learning model using EfficientNet-B7 to classify diabetic retinopathy stages from retinal fundus images.
It uses a dataset from APTOS 2019 Blindness Detection, available on Kaggle.
The notebook includes all key steps: dataset preparation, preprocessing, model building, training, evaluation, and visualization.

📂 Dataset
Source: https://www.kaggle.com/aitude/aptos-augmented-images

The dataset includes retinal images labeled according to diabetic retinopathy severity:
  0: No DR
  1: Mild
  2: Moderate
  3: Severe
  4: Proliferative DR

Data Split
  Training set: 80%
  Validation set: 10%
  Test set: 10%
  
Classification Report
The classification report summarizes the model’s precision, recall, and F1-score across the five diabetic retinopathy severity levels. Overall, the EfficientNet-B7 model achieved an accuracy of 95%, indicating strong generalization and robust feature learning from the retinal images.
  <img width="378" height="177" alt="image" src="https://github.com/user-attachments/assets/2bb432b6-b943-4d8e-9800-a00147901e88" />
  
* After 20 epoch for standard learning we aiming for 30 more epoch with fine-tune and turn learning rate to 1×10⁻4
  <img width="589" height="328" alt="image" src="https://github.com/user-attachments/assets/1dd10a77-8fef-4c14-a23a-2ddbda3802fa" />

* Confusion matrix
  <img width="757" height="528" alt="download (2)" src="https://github.com/user-attachments/assets/fe1db98c-10fa-4614-a94e-397c7435e2d8" />

* Testing on 15 image to testing accuracy
<img width="1702" height="1489" alt="download (3)" src="https://github.com/user-attachments/assets/f2b6d216-ba80-4b4d-b63a-e3e4edf393d3" />
<img width="1205" height="490" alt="download (4)" src="https://github.com/user-attachments/assets/ea8897fc-2965-4ede-9658-fbe40e9848e3" />

* Testing predict speed with 480 Sample
<img width="306" height="96" alt="image" src="https://github.com/user-attachments/assets/0b38e167-c187-4f9f-a002-9f46e8652c7b" />




