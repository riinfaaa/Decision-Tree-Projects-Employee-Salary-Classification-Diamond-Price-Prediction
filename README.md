# 💼  Decision-Tree-Projects-Employee-Salary-Classification-Diamond-Price-Prediction
This repository contains two practical machine learning mini-projects using Decision Tree models in Python and Scikit-learn. Both projects guide you through data preprocessing, feature encoding, model building, evaluation, and visualization.

## 1️⃣ Salary Classification with Decision Trees
Goal: Predict whether an employee’s salary exceeds $100,000, based on employer, job title, and degree.

📌 Problem Statement
How can we classify whether an employee earns more than 100k using only categorical job, degree, and company data?

🧠 Solution Overview
Classification task using a Supervised ML: Decision Tree Classifier.
Encodes categorical variables (e.g., company, job, degree).
Predicts high earners (salary_more_then_100k).

🧩 Features
Step-by-step, clean Colab notebook.
Handles data cleaning and label encoding for categories.
Builds and tunes a decision tree classifier.
Provides tables comparing true and predicted salary classes.
Example prediction output for easy inspection.
Visualizes tree structure (via Matplotlib).

📂 Dataset
Sample: salaries.csv
company (e.g., "google", "facebook", "abc pharma")
job (e.g., "sales executive", "business manager", ...)
degree ("bachelors", "masters")
salary_more_then_100k (0 = No, 1 = Yes)

🛠️ Tech Stack
Tool	Purpose
Python	Programming language
Pandas	Data manipulation
Scikit-learn	ML modeling
Matplotlib	Visualization

## 2️⃣ Diamond Price Prediction with Decision Trees
Goal: Predict the price of a diamond given its physical and categorical attributes using decision trees.

📌 Problem Statement
How can we predict diamond prices with features that include both categorical (e.g., cut, color, clarity) and numerical data (e.g., carat, dimensions, depth)?

🧠 Solution Overview
Regression task (typically; could also be classification for price brackets).
Handles text fields with label encoding (cut, color, clarity).
Trains a Decision Tree model to fit price based on all attributes.

🧩 Features
Colab-based
Data cleaning and type conversion for mixed features.
Feature encoding for cut, color, clarity.
Flexible for both regression and classification tasks.
Facilitates visualization of results and model performance.

📂 Dataset
Sample: diamonds.csv
Numerical: carat, depth, table, x, y, z, price
Categorical: cut, color, clarity

🛠️ Tech Stack
Tool	Purpose
Python	Programming language
Pandas	Data manipulation
Scikit-learn	ML modeling
Matplotlib	Visualization


🍰 What You’ll Learn
Data cleaning: Dealing with categorical and missing data.
Feature engineering: Label encoding for text features.
Modeling: Training and tuning Decision Tree models.
Evaluation: Comparing predictions to actuals in table form.
Visualization: Plot model structure and outputs.

🔗 Usage
Open the Google Colab notebooks.
Upload the datasets (salaries.csv, diamonds.csv)
Run each cell step by step—follow inline comments for explanations.


These projects provide a practical introduction to decision trees for both classification and regression, using highly interpretable examples from HR analytics and pricing prediction.

