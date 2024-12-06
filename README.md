# MANOJAVAM-The-AI-Health-Disease-Predictor
![IMG](https://github.com/onkar-2006/MANOJAVAM_the_health_predictor/blob/main/Screenshot%202024-11-18%20163556.png)



MANOJAVAM is an AI-powered platform designed to predict potential health risks based on medical and lifestyle data. By analyzing key health metrics such as blood pressure, cholesterol levels, age, and lifestyle habits, the system offers personalized insights and recommendations to help individuals prevent chronic diseases like heart disease, hypertension, and cancer.



Features:
Health Risk Predictions: Leverages AI to predict the likelihood of serious health conditions based on user data.
Personalized Insights: Provides tailored health recommendations to promote a healthier lifestyle.
User-Friendly Interface: Simple and intuitive design that makes health data accessible to everyone.
Data Security: Built with robust encryption to ensure user data privacy and security.
Actionable Recommendations: Helps users make informed decisions about their health to prevent future complications.



Technologies Used:

Artificial Intelligence (AI): Machine learning models for risk prediction.
Python: For implementing the AI models and backend logic.
Flask: Web framework for building the platform.
HTML/CSS/JavaScript: Frontend development for a responsive user interface.
SQLite/MySQL: Database for storing user data securely.


#### Evaluation Metrics  
```markdown
## Evaluation Metrics  

- **Accuracy**: Measures how often the model makes correct predictions.  
- **Precision & Recall**: Used for imbalanced data to assess the model’s robustness.  
- **F1-Score**: Harmonic mean of precision and recall.  

- **Blood Pressure Model**:  
  - Accuracy: 99%  

**Evaluation Results:**  
- **Heart disease Model**:  
  - Accuracy: 90%  
  

## Model Architecture  

- **Heart disease Prediction**: Logistic Regression with an accuracy of 98 HUGGING FACE LINK-https://huggingface.co/onkar2006/heart_disease_prediction_model/blob/main/heart-attack-prediction-351a75.ipynb%.  
- **Diabetes Prediction**: Random Forest Classifier with an accuracy of 99%.  
The models utilize scikit-learn for implementation and are trained on a dataset with over 5,000 samples.  

## data set- diabetes2.csv
## SAMPLE DATA FOR THE Diabetes USED
Pregnancies	Glucose	BloodPressure	SkinThickness	Insulin	BMI	Diabetes PedigreeFunction	   Age	 Outcome
2         	138	     74	            35	          100 	  33.6	       0.127              25	 Yes
5	          145	     80	            28	          105	  39.3	         0.263	            35	  No

Field Descriptions for diabetes Dataset:
Pregnancies: The number of times the patient has been pregnant.
Glucose: Plasma glucose concentration (mg/dL).
BloodPressure: Diastolic blood pressure (mmHg).
SkinThickness: Thickness of the triceps skinfold (mm).
Insulin: Serum insulin concentration (μU/mL).
BMI: Body Mass Index (kg/m²).
DiabetesPedigreeFunction: A score based on family history indicating the likelihood of diabetes.
Age: Age of the patient (years).
Outcome: Whether the patient has diabetes (Yes) or not (No).


## DATA USED -HEART.CSV DATASET-LINK-https://huggingface.co/datasets/buio/heart-disease
## SAMPLE DATA USED  FOR THE HEART  DISEASE PREDICTION
age	sex	cp	trestbps	chol	fbs	restecg	thalach	exang	oldpeak	slope	ca	thal	target
52	 1	0	  125	      212	   0	  1	     168	   0	    1	      2	   2	 3	   0
53	 1	0	  140	      203	   1	  0	     155	   1	   3.1	    0	   0	 3	   0

Field Descriptions for Heart Disease Dataset:

Age: Age of the patient (years).
Sex: Gender of the patient (1 = Male, 0 = Female).
CP: Chest pain type (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
Trestbps: Resting blood pressure (mmHg).
Chol: Serum cholesterol (mg/dL).
Fbs: Fasting blood sugar (1 = > 120 mg/dL, 0 = <= 120 mg/dL).
Restecg: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy).
Thalach: Maximum heart rate achieved during exercise.
Exang: Exercise induced angina (1 = yes, 0 = no).
Oldpeak: Depression induced by exercise relative to rest (measured in depression units).
Slope: Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).
Ca: Number of major vessels colored by fluoroscopy (0-3).
Thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
Target: Presence of heart disease (0 = No, 1 = Yes).


