# Codveda-Technology-Data-Science-Internship-Level-2-Intermediate-Task2
Intermediate (level 2) Task 2: Classification with Logistic  Regression 
🌸 Iris Species Classification - ML Classifier Comparison
This project is part of my Data Science Internship Task where I performed multi-class classification on the popular Iris dataset using multiple machine learning models.

📌 Objective
To classify iris flowers into their respective species (Setosa, Versicolor, Virginica) using:

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

🛠️ Key Steps
Loaded and cleaned Iris dataset from CSV

Scaled features using StandardScaler

Encoded species labels into numeric values

Split data into training/testing sets (stratified)

Trained and evaluated multiple ML models

Plotted ROC curves for each classifier

📊 Models & Results
Model	Accuracy
Logistic Regression	✅ ~96%
Random Forest	✅ ~98%
SVM (Support Vector Machine)	✅ ~97%

📈 ROC curves were plotted using a One-vs-Rest strategy for multi-class evaluation.

🧠 Tools & Libraries
Python (Pandas, NumPy)

Scikit-learn

Seaborn & Matplotlib for visualization

📂 File Structure
iris.csv – Dataset used

iris_classification.py – Full project code

README.md – Project documentation

🎯 Learnings
This project enhanced my understanding of:

Classification algorithms

ROC/AUC interpretation in multi-class

Data preprocessing & feature scaling

Evaluation metrics like precision, recall, F1-score

🚀 Output Visuals
Confusion Matrix

ROC Curves (for each species per classifier)

Classification reports for each model

