**`BRAIN STROKE PREDICTION`**

This project involves developing a machine learning model to predict the likelihood of a brain stroke based on various physiological parameters. The project utilizes four different machine learning algorithms, including Decision Tree Classification, Random Forest Classification, KNN, Gradient Boosting, and XGBoost Classification. Among these, XGBoost Classifier performed the best with an accuracy of approximately 93.66%.

**`TABLE OF CONTENTS`**

1. Data Description
2. Installation
3. Usage
4. Data Preprocessing
5. Algorithms Compared
6. Results
7. Conclusion

**`DATA DESCRIPTION`**

The dataset used in this project is the Brain Stroke Prediction Dataset from Kaggle. It contains 4981 records with 11 features, including age, gender, hypertension, heart disease, ever married, work type, residence type, avg glucose level, bmi, smoking status, and alcohol consumption.

**`INSTALLATION`**

1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-learn
6. Imbalanced-learn

You can install them using pip: `pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn`

**`USAGE`**

To use this project, follow these steps:

1. Load the dataset.
2. Preprocess the data.
3. Train the models.
4. Evaluate the models.
5. Compare the results.

**`DATA PREPROCESSING`**

1. **Label Encoding**: Convert categorical variables into numerical variables using label encoding.
2. **Data Balancing**: Balance the dataset using SMOTE (Synthetic Minority Over-sampling Technique).
3. **Standard Scaling**: Scale the data using standard scaling.

**`ALGORITHMS COMPARED`**

1. **Random Forest**: An ensemble learning method that operates by constructing multiple decision trees and merging them together.
2. **Decision Tree**: A simple yet powerful classification method that splits the population or sample into two or more homogeneous sets based on the most significant splitter/differentiator in input variables.
3. **K-Nearest Neighbors (KNN)**: A simple, instance-based learning algorithm that classifies instances based on their similarity to instances in the training dataset.
4. **Gradient Boosting**: A boosting technique that builds an additive model in a forward stage-wise fashion, allowing for the optimization of arbitrary differentiable loss functions.
5. **XGBoosting**: An optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable.

**`RESULTS`**

The XGBoosting model achieved the highest accuracy of 93.66%.

**`CONCLUSION`**

XGBoosting outperformed other models in predicting brain stroke occurrence. It is recommended to use XGBoosting for this prediction task.

**`LICENSE`**

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
