# Thyroid Disease Detection Using Machine Learning

This project aims to automate thyroid disease diagnosis using machine learning. It classifies patients into **Normal**, **Hypothyroid**, and **Hyperthyroid** based on clinical test results such as TSH, T3, T4 levels and demographic features.

## Overview

This project uses multiple machine learning models to predict thyroid conditions from patient data. The pipeline includes preprocessing, training, evaluation, and visualization. It is designed to assist healthcare professionals in identifying thyroid dysfunction early and accurately.

## Key Features

- Data preprocessing, including handling of missing values, normalization, and class imbalance using techniques like SMOTE.
- Multiple machine learning models: Random Forest, Gradient Boosting, SVM, etc.
- Model explainability using feature importance, confusion matrix, and ROC/PR curves.
- Evaluation metrics include accuracy, precision, recall, and F1-score.
- Visual insights via correlation heatmaps and feature distributions.
- Healthcare application focus for early diagnosis support.

## Dataset

**Source**: UCI Thyroid Disease Dataset

**Features Used**:
- Clinical: `TSH`, `T3`, `TT4`, `T4U`, `FTI`
- Demographic: `age`, `sex`, `pregnant`
- Medical history: `thyroid_surgery`, `lithium_use`

**Target variable**: `Thyroid_status`  
**Classes**: Normal, Hypothyroid, Hyperthyroid  
**Samples**: 3772 records  
**Class imbalance**: ~92% Normal, ~4% Hypo, ~4% Hyper

## Installation

```bash
git clone https://github.com/yourusername/thyroid-detection-ml.git
cd thyroid-detection-ml
pip install -r requirements.txt
jupyter notebook thyroid-detection.ipynb
```

## 📂 Project Structure
```
thyroid-detection-ml/
├── data/                    # Dataset files
│   └── thyroidDF.csv
├── notebooks/               # Jupyter notebooks
│   └── Thyroid_Detection_ML.ipynb
├── src/                     # Source code
│   ├── train.py             # Training script
│   └── utils.py             # Helper functions
├── images/                  # Visualizations
├── requirements.txt         # Dependencies
└── README.md
```


## Model Results

| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|-----------|--------|----------|
| Random Forest      | 98.1%    | 0.95      | 0.96   | 0.95     |
| Gradient Boosting  | 97.8%    | 0.94      | 0.94   | 0.94     |
| SVM                | 95.3%    | 0.91      | 0.91   | 0.91     |

**Best performing model**: Random Forest  
**Evaluation**: 5-fold cross-validation

## Future Work

- Add deep learning model support  
- Expand classification granularity (e.g., subclinical types)  
- Integrate with hospital management or diagnosis systems  
- Real-time data ingestion and dashboard visualizations

## Author

**Gopi Raju Rajolu**  
Email: gopirajunl.r@gmail.com  
Location: Fairborn, Ohio



<img width="840" alt="Screenshot 2025-04-11 at 19 09 15" src="https://github.com/user-attachments/assets/5a373a48-2f08-42c2-a9a3-1a630305e261" />
<img width="841" alt="Screenshot 2025-04-11 at 19 09 01" src="https://github.com/user-attachments/assets/8ad1c9f2-daab-4956-8265-08846c728671" />
<img width="841" alt="Screenshot 2025-04-11 at 19 08 08" src="https://github.com/user-attachments/assets/5e884be6-8b54-4797-986f-40edeaaef9e7" />
<img width="844" alt="Screenshot 2025-04-11 at 19 07 51" src="https://github.com/user-attachments/assets/f9fad506-bb26-44fe-b5dc-0b436a34ef71" />
<img width="845" alt="Screenshot 2025-04-11 at 19 07 37" src="https://github.com/user-attachments/assets/59dace1c-34d2-40df-a394-e09af6f7868e" />
<img width="1183" alt="Screenshot 2025-04-11 at 19 07 11" src="https://github.com/user-attachments/assets/3a51b575-0b96-498c-ab97-b09ad253b569" />
<img width="516" alt="Screenshot 2025-04-11 at 19 06 51" src="https://github.com/user-attachments/assets/8acb4af1-92f2-46a2-a7ee-5abffe567abc" />
<img width="514" alt="Screenshot 2025-04-11 at 19 06 41" src="https://github.com/user-attachments/assets/d4743568-bdde-421d-a0ef-142193707fc0" />
<img width="516" alt="Screenshot 2025-04-11 at 19 06 31" src="https://github.com/user-attachments/assets/d18b5834-38b6-4e05-bae8-cb3671dc3a31" />
<img width="513" alt="Screenshot 2025-04-11 at 19 06 18" src="https://github.com/user-attachments/assets/d7339e50-1742-4652-b2cd-f6f0537b10f9" />
<img width="516" alt="Screenshot 2025-04-11 at 19 06 08" src="https://github.com/user-attachments/assets/5c3ac7e7-2407-4506-b4a2-b3698165cccb" />
<img width="677" alt="Screenshot 2025-04-11 at 19 05 51" src="https://github.com/user-attachments/assets/19308017-6260-4125-92a0-ade440e9e23b" />
<img width="669" alt="Screenshot 2025-04-11 at 19 05 36" src="https://github.com/user-attachments/assets/bb85812f-650f-49bc-961e-966834fde1d5" />
<img width="687" alt="Screenshot 2025-04-11 at 19 05 05" src="https://github.com/user-attachments/assets/99b18fe3-4cef-4e1a-8f56-0ea2f39a239b" />
<img width="658" alt="Screenshot 2025-04-11 at 19 04 49" src="https://github.com/user-attachments/assets/c212df04-1722-46c1-a918-bd3912f4c543" />



