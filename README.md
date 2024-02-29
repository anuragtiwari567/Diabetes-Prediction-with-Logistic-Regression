# Diabetes Prediction with Logistic Regression


# lab-flask

<!-- ![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png) -->


To run flask application 

```
python app.py
```


To access your flask application open new tab in and paste the url:
```
https://{your_url}.app:5000/
```

## Overview
Diabetes is a prevalent health concern globally, and early detection can significantly impact patient outcomes. This project aims to predict whether an individual is diabetic or not based on several input features.

## Features Used for Prediction
- **Glucose**: Plasma glucose concentration (mg/dL).
- **Pregnancies**: Number of times pregnant.
- **Blood Pressure**: Diastolic blood pressure (mm Hg).
- **Skin Thickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg / (height in meters)^2).
- **Diabetes Pedigree Function**: Represents the likelihood of diabetes based on family history.
- **Age**: Age in years.

## Target Variable
- **Output Label**: “Diabetic” or “Not Diabetic”

## Project Structure
1. **Data Collection and Exploration:**
   - Load the dataset.
   - Explore the data (check for missing values, summary statistics, etc.).
2. **Data Preprocessing:**
   - Handle missing values (impute or drop).
   - Normalize or standardize features.
   - Split the data into training and testing sets.
3. **Model Building:**
   - Train a logistic regression model using the training data.
   - Tune hyperparameters if necessary.
4. **Model Evaluation:**
   - Evaluate the model’s performance using metrics such as accuracy, precision, recall, F1-score, and ROC curve.
   - Confusion matrix to understand true positives, true negatives, false positives, and false negatives.
5. **Trained Model:**
   - Save the trained model for future use.
6. **Deployment Platform (AWS):**
   - Deploy the model on Amazon Web Services (AWS) for real-time predictions.
7. **Usage:**
   - Provide clear instructions on how to use the deployed model for predictions.
   - Include sample code or API endpoints.
