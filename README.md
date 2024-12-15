# Heart-diesease-Prediction

This project focuses on predicting the presence of heart disease using machine learning techniques. The dataset includes various health-related attributes like age, cholesterol, blood pressure, and more. A logistic regression model is trained and evaluated to determine the likelihood of heart disease in individuals.

Table of Contents
	1.	Project Overview
	2.	Dataset Description
	3.	Technologies Used
	4.	Project Workflow
	5.	How to Run the Project
	6.	Results and Insights
	7.	Visualization
	8.	Contributing

 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes.
This project uses a supervised machine learning model (Logistic Regression) to predict the presence of heart disease based on medical parameters.


Dataset Description

The dataset used in this project contains the following features:
	•	Age: Age of the individual.
	•	Sex: Gender of the individual (0 = Female, 1 = Male).
	•	CP: Chest pain type.
	•	Trestbps: Resting blood pressure.
	•	Chol: Cholesterol levels.
	•	FBS: Fasting blood sugar (>120 mg/dl: 1 = True, 0 = False).
	•	Restecg: Resting electrocardiographic results.
	•	Thalach: Maximum heart rate achieved.
	•	Exang: Exercise-induced angina (1 = Yes, 0 = No).
	•	Oldpeak: ST depression induced by exercise.
	•	Slope: Slope of the peak exercise ST segment.
	•	Ca: Number of major vessels (0–3).
	•	Thal: Thalassemia status.
	•	Target: (0 = No Heart Disease, 1 = Heart Disease).



 Technologies Used
	•	Programming Language: Python
	•	Libraries:
	•	NumPy for numerical operations
	•	Pandas for data manipulation
	•	Matplotlib for data visualization
	•	Scikit-Learn for machine learning



 Project Workflow
	1.	Data Collection: The heart disease dataset is loaded and explored.
	2.	Data Preprocessing:
	•	Check for missing values.
	•	Feature scaling to normalize the data.
	3.	Model Training:
	•	Logistic Regression is used for prediction.
	•	The dataset is split into training and testing sets.
	4.	Evaluation: The accuracy of the model is evaluated using metrics like accuracy_score.
	5.	Prediction: Model is tested with new input data to predict heart disease status.



 Results and Insights
	•	The Logistic Regression model achieved an accuracy of 85% on the training data.
	•	Age distribution showed that individuals between 50–55 years are at the highest risk of heart disease.
	•	Feature scaling and preprocessing steps significantly improved model performance.
 

