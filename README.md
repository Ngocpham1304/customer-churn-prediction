# Customer churn prediction
AI Final Project - YZU - Group 4

## Overview
This project involves improvements in data preprocessing and enhance Artificial Neural Network (ANN) for better result of predicting customer churn. The dataset used contains various customer attributes, and the ANN with improvements is trained to predict whether a customer is likely to leave the bank.

## Files
- **code/churn_ann_clean_submission.ipynb**: Jupyter Notebook containing the code for EDA, data preprocessing, model building, training, and evaluation.
- **data/Churn_Modelling.csv**: Dataset used for training and testing.

## Environment setup and requirements
- Google Colab.

## Step to run the project
1. Open Google Colab at https://colab.research.google.com/.
2. On **Open Notebook** window, choose **Github** and fill in the Project's Github link (https://github.com/Ngocpham1304/customer-churn-prediction), then choose path **code/churn_ann_clean_submission.ipynb**.
<img width="986" height="760" alt="image" src="https://github.com/user-attachments/assets/b7ff3e70-5980-4c77-b99f-cc5df58294f9" />

3. Download dataset from the Project's Github link (in folder **data/** https://github.com/Ngocpham1304/customer-churn-prediction/blob/main/data/Churn_Modelling.csv).
4. Upload dataset to Google Colab.
<img width="666" height="393" alt="image" src="https://github.com/user-attachments/assets/d2944664-ea3e-4b97-bc7f-e689316e74d9" />

5. Choose **Run all** to run the project.
<img width="640" height="386" alt="image" src="https://github.com/user-attachments/assets/f71e717e-f03d-4417-bc77-fbf8e95d7037" />

## Result Summary
<img width="705" height="184" alt="image" src="https://github.com/user-attachments/assets/c7901790-75b2-4ef8-b5cd-ee9a89466278" />

- **Accuracy**
  - Only +1–2% improvement
  - Expected due to class imbalance
- **ROC-AUC**
  - Stronger ranking ability
  - Better separation between churners and non-churners
- **Recall**
  - +20% or more
  - Much better churn detection
