🏥 Patient Survival Prediction Using Machine Learning
This project aims to predict patient survival outcomes based on clinical and demographic data, using exploratory data analysis (EDA) and a range of supervised machine learning models.

🔍 Dataset Overview
The dataset consists of 91,000 rows and 85 columns, each representing a patient and various clinical indicators such as age, sex, treatment type, and survival status.
The target variable is a binary indicator of patient survival (1 = Survived, 0 = Did not survive).
Data imbalance was observed (approximately 72% survived, 28% did not survive), prompting careful metric selection beyond accuracy.

📊 Analytical Overview
EDA & Preprocessing:
Visualized feature distributions to understand key drivers of survival.
Used heatmaps to identify correlations and reduce multicollinearity.
Performed label encoding on categorical features and scaled continuous variables.
Outliers and missing values were addressed using domain-informed thresholds and median imputation.

🤖 Model Implementation & Results
Trained and evaluated the following models:
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Support Vector Machine (SVM)

Best Performing Model: Random Forest Classifier

Accuracy: 85.6%
Precision: 0.83
Recall: 0.87
F1-score: 0.85

Strong performance on minority class (non-survivors) due to balanced depth and ensemble averaging.

📈 Tools & Libraries
Python, Jupyter Notebook
Pandas, NumPy, Matplotlib, Seaborn
Scikit-learn (modeling, metrics, preprocessing)

💡 Outcome
This project demonstrates a complete data science workflow for a high-impact healthcare prediction problem, showcasing how machine learning models can help predict patient survival and support medical decision-making.# PatientSurvivalPrediction
