
# Used Car Price Prediction using XGBoost

This repository contains the solution for the Kaggle Playground Series - Season 4, Episode 9 competition. The task involves building a predictive model to estimate the target variable using advanced machine learning techniques, primarily using the **XGBoost** algorithm.

---

## **Table of Contents**
1. [Problem Statement](#problem-statement)
2. [Dataset](#dataset)
3. [Solution Workflow](#solution-workflow)
4. [Dependencies](#dependencies)
5. [Results](#results)
6. [Author](#author)
7. [Contact](#contact)

---

## **Problem Statement**
The goal of this project is to create a predictive model using the provided dataset to optimize the evaluation metric. The key steps include:
- Performing Exploratory Data Analysis (EDA).
- Preprocessing the data.
- Training a model using XGBoost.
- Generating predictions for the test dataset.

[Visit the Kaggle competition page](https://www.kaggle.com/competitions/playground-series-s4e9/overview) for more details.

---

## **Dataset**
The dataset used in this project can be downloaded from the competition [data page](https://www.kaggle.com/competitions/playground-series-s4e9/data). It contains:
- A training dataset with features and target variable.
- A test dataset with features for predictions.
- A sample submission file for reference.

---

## **Solution Workflow**
1. **Exploratory Data Analysis (EDA):**
   - Understand the structure of the dataset.
   - Visualize feature distributions and relationships.
   - Handle missing values and outliers.

2. **Data Preprocessing:**
   - Encode categorical features.
   - Scale numerical features.
   - Split the data into training and validation sets.

3. **Model Training:**
   - Train an XGBoost model on the preprocessed training data.
   - Evaluate model performance using metrics like AUC-ROC or RMSE.

4. **Hyperparameter Tuning:**
   - Optimize the model using techniques like Grid Search or Optuna.

5. **Prediction and Submission:**
   - Generate predictions for the test dataset.
   - Save predictions in the required format for submission.

---

## **Dependencies**
The following libraries are used in this project:
- Python 3.8 or above
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Optuna (optional, for hyperparameter tuning)

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## **Results**
The model achieved the following metrics (example placeholder):

- Validation RMSE: `1.234`
- Public Leaderboard Score: `0.5678`

Check the detailed analysis and results in the notebook.

---

## **Author**
[Poulami Nandi](https://www.linkedin.com/in/poulami-nandi-a8a12917b/)

---

## **Contact**
- **Email:** [nandi.poulami91@gmail.com](mailto:nandi.poulami91@gmail.com)
- **GitHub Repository:** [Used Car Price Prediction](https://github.com/Poulami-Nandi/UsedCarPrice_XGB)
