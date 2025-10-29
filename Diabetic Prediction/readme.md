# Diabetes Prediction Project

This project aims to predict the likelihood of an individual having diabetes based on certain diagnostic measurements. It utilizes machine learning techniques for classification. This is **Day 2** of my 40-day ML project challenge.

## Project Overview

This project involves the following steps:

1.  **Import Dependencies:** Load necessary libraries such as `numpy`, `pandas`, and `scikit-learn`.
2.  **Load Data:** Read the diabetes dataset (commonly the PIMA Indians Diabetes dataset).
3.  **Data Preprocessing:** Handle missing values (if any), explore data distributions, and potentially standardize features.
4.  **Train-Test Split:** Divide the dataset into training and testing sets to evaluate model performance.
5.  **Model Training:** Train a classification model (e.g., Support Vector Machine (SVM)) on the training data.
6.  **Model Evaluation:** Assess the model's accuracy and potentially other metrics (like precision, recall, F1-score) on the test set.
7.  **Predictive System (Optional):** Create a simple function or script to predict diabetes for new input data based on the trained model.

## Dataset

The dataset typically includes features such as:

* Pregnancies
* Glucose level
* Blood Pressure
* Skin Thickness
* Insulin level
* Body Mass Index (BMI)
* Diabetes Pedigree Function
* Age
* Outcome (0: Non-Diabetic, 1: Diabetic)



## Model & Performance

* **Model Used:** Support Vector Machine (SVM) Classifier 
* **Accuracy:** ~78% on Training data and ~75% on Testing data

## Requirements

* Python
* NumPy
* Pandas
* Scikit-learn


Install dependencies using pip:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

## How to Use
Clone the repository or download the project files.

Ensure you have the required libraries installed.

Run the Jupyter Notebook (e.g., diabetes_prediction.ipynb) or Python script to see the data processing, model training, and evaluation steps.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
