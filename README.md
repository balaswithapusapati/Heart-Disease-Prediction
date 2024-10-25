# Heart Disease Prediction using SVM

This project implements a heart disease prediction model using Support Vector Machine (SVM) on a dataset containing various health-related attributes.

## Introduction
Heart disease is a major health concern worldwide. This project aims to build a predictive model to identify the presence of heart disease based on various health indicators using SVM.

## Dataset
The dataset used for this project dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. While it contains 76 attributes, all published experiments typically refer to using a subset of 14 of them. The key features include:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **ChestPainType**: Type of chest pain experienced
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Serum cholesterol in mg/dl
- **FastingBS**: Fasting blood sugar > 120 mg/dl
- **RestingECG**: Results of resting electrocardiogram
- **MaxHR**: Maximum heart rate achieved
- **ExerciseAngina**: Exercise induced angina (yes/no)
- **Oldpeak**: ST depression induced by exercise relative to rest
- **ST_Slope**: Slope of the peak exercise ST segment
- **NumMajorVessels**: Number of major vessels (0-3) colored by fluoroscopy
- **Thal**: Thalassemia (normal, fixed defect, reversible defect)
- **Target**: Presence of heart disease (1) or absence (0)

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using pip:

```bash
pip install pandas numpy scikit-learn
```

## Usage
 1. Run the model:

```bash
python code.py
```
 2. The model will output the validation and test accuracies along with the classification report.

## Results
* Validation Accuracy: 94.15%
* Test Accuracy: 90.73%
