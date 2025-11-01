## 🩺 Diabetes Classification using Decision Tree

This project aims to predict whether a person has diabetes based on various medical attributes using a **Decision Tree Classifier** 
The dataset includes several health indicators such as glucose level, blood pressure, BMI, and family history of diabetes.

## 📊 Dataset Description

The dataset consists of the following columns:
- **Pregnancies** — Number of times the patient has been pregnant
- **Glucose** — Plasma glucose concentration
- **BloodPressure** — Diastolic blood pressure (mm Hg)
- **SkinThickness** — Triceps skinfold thickness (mm)
- **Insulin** — 2-Hour serum insulin (mu U/ml)
- **BMI** — Body Mass Index (weight in kg / height in m²)
- **DiabetesPedigreeFunction** — Likelihood of diabetes based on family history
- **Age** — Age of the patient
- **Diabetes** — Target variable (1 = has diabetes, 0 = no diabetes)

## 🎯 Objective
To build a Decision Tree model that classifies whether a person has diabetes or not using physiological and hereditary data.

## ⚙️ Workflow
-**Data Wrangling** — Load, assess, and clean the dataset.
- **Exploratory Data Analysis (EDA)** — Visualize data patterns and correlations.
- **Modeling** — Train and evaluate a Decision Tree Classifier using scikit-learn.
- **Evaluation** — Measure accuracy, precision, recall, and F1-score.

## 🧠 Modeling with Decision Tree
The Decision Tree algorithm was implemented using sklearn.tree.DecisionTreeClassifier with a random state of 3 to ensure reproducibility.
The model is designed to interpret the relationships between features and predict diabetes likelihood effectively.


The model provides insights into which medical factors contribute the most to diabetes prediction, such as glucose level and BMI.
Through visualization and model evaluation, users can better understand decision paths and patient risk factors.
