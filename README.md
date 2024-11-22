# Heart Attack Prediction Dataset

## Overview

This repository contains a dataset aimed at predicting heart attack risks, featuring **8,763 records** and **26 attributes** related to cardiovascular health. It serves as a valuable resource for developing predictive models and exploring the impact of lifestyle choices on heart health outcomes.

## Project Goal

The goal of this project is to develop and validate predictive models for heart attack risk using the provided dataset. By analyzing the correlations between various health metrics, lifestyle factors, and demographic information, we aim to identify key risk factors and improve early detection methods for heart disease.

## Dataset Details

- **Total Records:** 8,763
- **Total Attributes:** 26
- **Key Features:**
  - **Demographics:**
    - **Age:** Age of the individual (in years).
    - **Sex:** Gender of the individual (1 = male, 0 = female).
    - **Country:** The country of residence, providing a geographical context.
  - **Health Metrics:**
    - **Cholesterol Levels:** Measured in mg/dL, indicating the total cholesterol level.
    - **Blood Pressure:** Systolic and diastolic measurements (in mmHg).
    - **Heart Rate:** Beats per minute, indicating the individual's heart rate.
  - **Lifestyle Factors:**
    - **Smoking Status:** Whether the individual is a smoker (1 = yes, 0 = no).
    - **Diet:** Categorized as Healthy, Average, or Unhealthy, based on dietary choices.
    - **Exercise Habits:** Frequency of physical activity (e.g., none, moderate, vigorous).
    - **Body Mass Index (BMI):** A calculated value based on height and weight.
  - **Medical History:**
    - **Diabetes:** Indicates if the individual has diabetes (1 = yes, 0 = no).
    - **Family History of Heart Disease:** Indicates if there is a family history of heart disease (1 = yes, 0 = no).
    - **Previous Health Issues:** Any prior medical conditions related to cardiovascular health.

- **Data Quality:**
  - **Missing Values:** The dataset is free from missing values, ensuring reliability in analysis.
  - **Outliers:** Initial exploration may reveal outliers in health metrics; further analysis is recommended.

## Example of Dataset

Below is an example of the dataset structure:

![Dataset Example](Data%20set/head%20of%20dataset.png)

## Evaluation Results
1.**Random Forest achieved the highest accuracy (0.6435), making it the most reliable for general use cases.**
2.**KNN showed the highest precision (0.55) and the best F1-score (0.41), indicating its strength in correctly classifying positive samples.**
3.**Other models, including Decision Tree, SVM, and Naive Bayes, had comparable performance across all metrics.**

This repository evaluates several machine learning classification models, including Decision Tree (Gini and Entropy), Random Forest, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Naive Bayes, using four key performance metrics: accuracy, which measures overall correctness; precision, the proportion of true positives among predicted positives; recall, the ability to identify all relevant positive cases; and F1-score, the harmonic mean of precision and recall. The goal is to provide a comparative analysis of these models based on these metrics to assist in selecting the best algorithm for a given classification task.


![Evaluation](Data%20set/eval.png)
## Usage

1. **If you want to see the General data information, look at the [Heart Attack Prediction General data information.ipynb](Heart%20Attack%20Prediction%20General%20data%20information.ipynb) file.**
2. **If you want to see the Random Forest model execution details, look at the [Implementation of random forest algorithm](Implementation%20of%20random%20forest%20algorithm/Random%20Forest%20-%20ORG%20_%20CODE.ipynb) file.**
3. **If you want to see the Decision Tree model execution details, look at the [Implementation of Decision Tree algorithm](Implementation%20of%20Decision%20Tree%20algorithm/Decision%20Tree.ipynb) file.**
4. **If you want to see the KNN model execution details, look at the [Implementation of KNN algorithm](Implementation%20of%20KNN%20algorithm/KNN.ipynb) file.**
5. **If you want to see the Naive bayes model execution details, look at the [Implementation of Naive bayes algorithm](Implementation%20of%20Naive%20bayes%20algorithm/Naive%20bayes.ipynb) file.**
6. **If you want to see the SVM execution details, look at the [Implementation of SVM algorithm](Implementation%20of%20SVM%20algorithm/SVM.ipynb) file.**
7. **Clone the repository:**
   ```bash
   git clone https://github.com/AlirezaLashkar/HeartAttackPredictionDataset.git


## References

- [Heart Attack Prediction Dataset - Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/heart-attack-prediction-dataset/data)
