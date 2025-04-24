# Thyroid-Detection-using-ML-Models

```markdown
# Thyroid Disease Detection Using Machine Learning

![Thyroid Gland](https://via.placeholder.com/800x400?text=Thyroid+Detection+ML)  *(Replace with a relevant image)*

## 📌 Overview
This project aims to **automate thyroid disease diagnosis** using machine learning. It classifies patients into **Normal, Hypothyroid, and Hyperthyroid** based on clinical test results (TSH, T3, T4 levels) and demographic features.

## 🎯 Key Features
- **Data Preprocessing**: Handles missing values, class imbalance, and feature scaling.
- **Multiple ML Models**: Compares Random Forest, Gradient Boosting, SVM, etc.
- **Explainability**: Feature importance and precision-recall curves.
- **Healthcare Focus**: Designed to assist doctors in early diagnosis.

## 📊 Dataset
- **Source**: [UCI Thyroid Disease Dataset]
- **Features**:
  - Clinical: `TSH`, `T3`, `TT4`, `T4U`, `FTI`
  - Demographic: `age`, `sex`, `pregnant`
  - Medical History: `thyroid_surgery`, `lithium_use`

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/thyroid-detection-ml.git
   cd thyroid-detection-ml
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage
1. Run the Jupyter notebook for EDA and modeling:
   ```bash
   jupyter notebook Final_TD.ipynb
   ```
2. To train and evaluate models:
   ```python
   python train.py
   ```

## 📈 Results
### Model Performance
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Gradient Boosting   | 95%      | 0.94      | 0.93   | 0.94     |
| Random Forest       | 93%      | 0.92      | 0.91   | 0.92     |

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

