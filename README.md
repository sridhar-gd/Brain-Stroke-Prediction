<p align="center"><img width=100% src="https://github.com/sridhar-gd/sridhar-gd/blob/main/Banner.png"></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.11+-blue.svg)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)


# BRAIN STROKE PREDICTION

The objective of this project is to identify individuals at high risk of stroke, enabling early intervention and prevention of irreversible damage or death using machine learning. It analyzes various factors such as age, heart disease, average glucose level, and hypertension to predict stroke occurrence. This end-to-end system can provide accurate predictions and proper analysis, helping medical professionals make informed decisions for patient care. While many previous studies have focused on heart attack prediction, ML-based stroke prediction has been explored less extensively, making this a significant area of research.


## Table of Contents

1. Data Description
2. Data Preprocessing
3. Models Used
5. Results
6. Deployment
7. License


## Data Description

The dataset used in this project is the Brain Stroke Prediction Dataset from Kaggle. It contains 4981 records with 11 features, including age, gender, hypertension, heart disease, ever married, work type, residence type, avg glucose level, bmi, smoking status, and alcohol consumption.- obj_ID = Object Identifier, the unique value that identifies the object in the image catalog used by the CAS
- gender: "Male", "Female" or "Other"
- age: age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married: "No" or "Yes"
- work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type: "Rural" or "Urban"
- avg_glucose_level: average glucose level in blood
- bmi: body mass index
- smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke: 1 if the patient had a stroke or 0 if not


## Data Preprocessing

- Label encoding is used to convert categorical variables into numerical variables.
- To address the class imbalance, we employed the Synthetic Minority Over-sampling Technique (SMOTE).
- Standard Scaler was employed to ensure that all features contribute equally to the model's learning process, preventing biases due to differing scales.


## Models Used

- **Random Forest**: An ensemble learning method that operates by constructing multiple decision trees and merging them together.
- **Decision Tree**: A simple yet powerful classification method that splits the population or sample into two or more homogeneous sets based on the most significant splitter/differentiator in input variables.
- **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies instances based on their similarity to instances in the training dataset.
- **Gradient Boosting**: A boosting technique that builds an additive model in a forward stage-wise fashion, allowing for the optimization of arbitrary differentiable loss functions.
- **XGBoosting**: An optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.


## Results

The XGBoosting model achieved the highest accuracy of 93.66%.
| Ranking    | Model                  | Accuracy    | 
| -----------|:-------------          |:-----:      |
| 1          | XGBoosting             | 93.66       |
| 2          | Random Forest          | 93.27       |
| 3          | Decision Tree          | 90.69       |
| 4          | K-Nearest Neighbors    | 86.67       |
| 5          | Gradient Boosting      | 85.81       |


## Deployment

Taking the model from development to deployment, Flask - a powerful web framework for Python - was utilized.


## License

MIT License

Copyright (c) 2024 Sridhar GD

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
