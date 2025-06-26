Project name: Heart disease prediction using AI
Overview
This project focuses on predicting the presence of heart disease using a dataset containing various medical attributes. The goal is to build a machine learning model that can accurately classify whether a patient has heart disease based on their medical data.

Dataset
The dataset used in this project is named heart.csv and contains the following features:

age: Age of the patient

sex: Gender of the patient (1 = male, 0 = female)

cp: Chest pain type (0-3)

trestbps: Resting blood pressure (mm Hg)

chol: Serum cholesterol (mg/dl)

fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

restecg: Resting electrocardiographic results (0-2)

thalach: Maximum heart rate achieved

exang: Exercise-induced angina (1 = yes, 0 = no)

oldpeak: ST depression induced by exercise relative to rest

slope: Slope of the peak exercise ST segment

ca: Number of major vessels colored by fluoroscopy (0-4)

thal: Thalassemia (0-3)

target: Presence of heart disease (1 = yes, 0 = no)

Project Steps
Data Loading: The dataset is loaded and inspected for initial understanding.

Data Cleaning:

Handling missing values by imputing with mean or median based on skewness.

Checking for and removing duplicate rows.

Data Preparation:

Separating the dataset into features (x) and target variable (y).

Splitting the data into training and testing sets (80% train, 20% test).

Model Building:

Using the K-Nearest Neighbors (KNN) algorithm for classification.

Training the model on the training set.

Model Evaluation:

Predicting on both training and testing sets.

Calculating accuracy, confusion matrix, and classification report to assess performance.

Results
Training Accuracy: 97.32%

Testing Accuracy: 94.74%

The model demonstrates high accuracy in predicting heart disease, making it a reliable tool for preliminary medical assessments.

How to Run
Ensure you have Python installed along with the required libraries (pandas, scikit-learn, numpy, seaborn, matplotlib).

Upload the heart.csv file to your working directory.

Run the Jupyter notebook Ai_Lab_Project_2025.ipynb to execute the project step-by-step.

Future Improvements
Experiment with other machine learning algorithms (e.g., Random Forest, SVM) to compare performance.

Perform hyperparameter tuning to optimize the KNN model.

Include feature engineering to enhance model accuracy.

Dependencies
Python 3.x

pandas

scikit-learn

numpy

seaborn

matplotlib

Author
Priyantu Das Antu
