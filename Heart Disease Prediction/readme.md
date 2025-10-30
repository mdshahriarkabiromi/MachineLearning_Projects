# Heart Disease Prediction Project

This project focuses on predicting the likelihood of an individual having heart disease based on various medical attributes from the Kaggle Heart Disease Dataset. It utilizes a Logistic Regression model for binary classification. This marks **Day 3** of my 40-day ML project challenge.

## Project Overview

This project follows a standard machine learning workflow:

1.  **Import Dependencies:** Necessary libraries such as `numpy`, `pandas`, and `scikit-learn` are imported.
2.  **Load Data:** The `heart_disease_data.csv` dataset from Kaggle is loaded into a pandas DataFrame.
3.  **Data Exploration & Preprocessing:**
    * Initial exploration is performed to understand the dataset's structure, identify data types, and check for missing values.
    * Feature scaling (e.g., using `StandardScaler`) might be applied depending on the model's sensitivity. *(Adjust if you performed scaling)*
4.  **Train-Test Split:** The dataset is split into training and testing sets (e.g., 80% for training, 20% for testing) to evaluate the model's performance on unseen data.
5.  **Model Training:** A **Logistic Regression** model is instantiated and trained on the preprocessed training data.
6.  **Model Evaluation:** The model's performance is assessed using accuracy scores on both the training and test sets.
7.  **Predictive System (Optional):** A small function demonstrates how to take new patient data as input and predict the likelihood of heart disease using the trained model.

## Dataset

* **Source:** [Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data) *(Note: Original Kaggle source might use `heart.csv`, but using the name you provided)*
* **Filename:** `heart_disease_data.csv`
* **Features:** The dataset includes 14 columns:
    * `age`: Age in years
    * `sex`: (1 = male; 0 = female)
    * `cp`: Chest pain type (0-3)
    * `trestbps`: Resting blood pressure (mm Hg)
    * `chol`: Serum cholestoral (mg/dl)
    * `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
    * `restecg`: Resting electrocardiographic results (0-2)
    * `thalach`: Maximum heart rate achieved
    * `exang`: Exercise induced angina (1 = yes; 0 = no)
    * `oldpeak`: ST depression induced by exercise relative to rest
    * `slope`: The slope of the peak exercise ST segment
    * `ca`: Number of major vessels (0-3) colored by flourosopy
    * `thal`: Thallium stress test result (1-3)
    * `target`: Diagnosis of heart disease (0 = no, 1 = yes)

## Model & Performance

* **Model Used:** Logistic Regression
* **Training Accuracy:** 85.0%
* **Testing Accuracy:** 81.9%

## Requirements

* Python
* NumPy
* Pandas
* Scikit-learn

Install dependencies using pip:
```bash
pip install numpy pandas scikit-learn
```
## How to Use
Ensure you have the heart_disease_data.csv dataset in your project directory.

Install the required Python libraries.

Execute the Jupyter Notebook or Python script containing the project code. The script will load data, train the model, evaluate it, and display the accuracy scores.
