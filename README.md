# Airline Passenger Recommendation Prediction Classification 

![image](https://github.com/user-attachments/assets/3428930f-83ae-46c3-a55a-d6a6b3adf99b)



This project focuses on analyzing and classifying airline passenger reviews using machine learning models. The goal is to predict whether a passenger would recommend the airline based on various review features, and extract actionable insights that airlines can use to improve customer satisfaction.



## 📁 Dataset Overview

* **Source**: Airline reviews from 2006 to 2019
* **Features**: 17 columns including ratings, cabin class, traveler type, etc.
* **Target Variable**: `recommended` (Yes/No)
* 

## 🔍 Project Workflow

1. **Data Preprocessing**

   * Converted date fields to datetime objects
   * Normalized rating scales
   * Handled missing values and cleaned columns

2. **Exploratory Data Analysis (EDA)**

   * Identified popular airlines, cabin preferences, and rating trends
   * Visualized key insights using bar plots, pie charts, line charts

3. **Statistical Testing**

   * Applied T-test, Chi-square, and ANOVA to test hypotheses
   * Evaluated relationships between traveler type, cabin class, and ratings

4. **Feature Engineering**

   * Encoded categorical variables
   * Feature importance assessed using filter method and tree-based models
   * **Dimensionality Reduction** was considered but not applied as performance was already optimal

5. **Modeling**

   * Models used: Decision Tree, Random Forest, XGBoost
   * Split: 70% train, 30% test
   * Evaluation: Accuracy, Precision, Recall, F1 Score



## 📊 Model Performance

| Model         | Accuracy   | Precision  | Recall | F1 Score   |
| ------------- | ---------- | ---------- | ------ | ---------- |
| Decision Tree | 93.25%     | 93.25%     | 92.71% | 92.98%     |
| Random Forest | 93.99%     | 94.07%     | 93.44% | 93.75%     |
| XGBoost       | **94.04%** | **94.21%** | 93.38% | **93.79%** |

XGBoost performed the best overall, followed closely by Random Forest.



## 🔎 Feature Importance

Top features contributing to recommendation prediction:

* **Value for Money**
* **Ground Service**
* **Cabin Service**
* **Seat Comfort**
* **Food & Beverage**
* **Entertainment**

Tree-based model explainability helped identify which features most influenced model decisions.



## 💡 Business Insights

The model enables airlines to:

* Predict which passengers are likely to recommend their service
* Identify improvement areas like service quality, comfort, and food
* Target key customer groups for better retention and satisfaction



## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn**
* **XGBoost**



## 📌 Conclusion

This project demonstrates how machine learning can uncover valuable insights from passenger feedback and assist airlines in enhancing service quality to drive loyalty and growth.



![image](https://github.com/user-attachments/assets/f6a7260a-18af-4821-a4a5-1ee6e2dd91c3)


