# Sonar vs Rock Prediction

This project uses a simple logistic regression model to classify sonar signals as either "Rock" (R) or "Mine" (M). The model is built using `scikit-learn` and `pandas`.

## Project Overview

The core of this project is in the `rock_mine_prediction.ipynb` Jupyter Notebook. The notebook walks through the following steps:

1.  **Import Dependencies:** Loads necessary libraries (`numpy`, `pandas`, `sklearn`).
2.  **Data Collection and Processing:** Loads the `sonar data.csv` dataset, which has no headers.
3.  **Data Exploration:** Checks the shape of the data (208 rows, 61 columns), displays the first few rows, and gets descriptive statistics.
4.  **Class Distribution:** Counts the number of samples for "Rock" (R: 97) and "Mine" (M: 111).
5.  **Train-Test Split:** Separates the 60 feature columns from the target label (column 60) and splits the data into training and testing sets.
6.  **Model Training:** Trains a `LogisticRegression` model on the training data.
7.  **Model Evaluation:** Measures the model's performance by calculating its accuracy on both the training and testing datasets.
8.  **Predictive System:** Includes an example of how to use the trained model to predict the class of a new, single sonar reading.

## Dataset

* **File:** `sonar data.csv`
* **Description:** This file contains 208 samples. Each row consists of 60 sonar readings (features) and a final column for the label (`R` or `M`).

## Model & Performance

A **Logistic Regression** model from `scikit-learn` is used for this classification task.

The model's performance, as seen in the notebook, is:
* **Training Data Accuracy:** 82.98%
* **Testing Data Accuracy:** 85.00%

## Requirements

To run this project, you will need Python and the following libraries:

* `numpy`
* `pandas`
* `scikit-learn`

You can install these dependencies using `pip`:
```bash
pip install numpy pandas scikit-learn
```
How to Use
Ensure you have the required libraries installed.

Open and run the rock_mine_prediction.ipynb notebook in a Jupyter environment.

The notebook will load the sonar data.csv, train the model, and output the accuracy scores.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
