Framingham Heart Disease Prediction — Data Science Project

Overview
This project analyzes the Framingham Heart Study dataset to understand the factors associated with cardiovascular disease (CVD) and build a predictive model that estimates a person's risk of developing heart disease.

The analysis includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation study of risk factors
- Feature engineering
- Multiple machine-learning classification models
- Model performance evaluation

Objectives
- Clean and preprocess medical and demographic data  
- Analyze trends and relationships among CVD risk factors  
- Build ML models to predict 10-year heart disease probability  
- Compare model performance and identify optimal classifier  
- Provide insights into key predictors of cardiovascular risk  

Dataset
Source: Framingham Heart Study  
File: framingham.csv

The dataset includes medical and lifestyle attributes such as:
- Age, Gender  
- Smoking behavior  
- Blood pressure  
- Cholesterol levels  
- Diabetes  
- Heart rate  
- Hypertension  
- Ten-year coronary heart disease (CHD) outcome  

Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

Project Workflow
1. Data Preprocessing
   - Handling missing values
   - Converting categorical variables
   - Scaling numerical features

2. Exploratory Data Analysis
   - Distribution plots
   - Boxplots for outliers
   - Correlation heatmaps
   - Risk-factor comparisons

3. Model Development
   Models used:
   - Logistic Regression
   - Random Forest Classifier
   - Decision Tree
   - KNN
   - SVM

4. Model Evaluation
   Metrics used:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC–AUC curve

Results
- Identified strong predictors of CHD (age, blood pressure, cholesterol, smoking).
- Achieved reliable performance with tuned classification models.
- Visualizations highlight key medical patterns and risk factors.

Repository Structure
Framingham-Heart-Disease-Analysis
 ├── data
 │    └── framingham.csv
 ├── notebooks
 │    └── Framingham_dataset_Heart_disease.ipynb
 ├── README.md

How to Run the Project
Clone the repository:
git clone https://github.com/Anshumanpandey01/framingham-heart-disease-analysis.git

Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

Run the notebook:
jupyter notebook Framingham_dataset_Heart_disease.ipynb

Conclusion
This project demonstrates how machine learning can help identify individuals at risk of heart disease based on medical and lifestyle factors. The results can support early prevention and informed medical decisions.

Author
Anshuman Pandey
Data Science & Analytics Enthusiast
