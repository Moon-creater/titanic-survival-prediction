This project aims to build a Machine Learning model to predict whether a passenger survived the Titanic disaster based on demographic and travel-related features.

The dataset used for this project is the Titanic dataset available on Kaggle.

This project demonstrates a complete end-to-end ML workflow including:

Data Cleaning

Feature Engineering

Data Preprocessing

Model Training

Model Evaluation

Cross Validation

📂 Dataset

The dataset contains information about individual passengers, including:

Passenger Class (Pclass)

Sex

Age

Number of Siblings/Spouses (SibSp)

Number of Parents/Children (Parch)

Fare

Embarked Port

Survival Status (Target Variable)

Target Variable:

Survived

0 → Did not survive

1 → Survived

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

⚙️ Project Workflow
1️⃣ Data Preprocessing

Filled missing values in Age using median.

Filled missing values in Embarked using mode.

Dropped Cabin column due to high missing ratio.

Scaled numerical features using StandardScaler.

Encoded categorical variables using OneHotEncoder.

2️⃣ Feature Engineering

Created FamilySize feature.

Created IsAlone feature.

3️⃣ Models Used

Logistic Regression

Random Forest Classifier

4️⃣ Model Evaluation

Accuracy Score

Classification Report

Confusion Matrix

5-Fold Cross Validation

📊 Results

The Random Forest model performed better compared to Logistic Regression.

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1-score

Cross-validation mean accuracy

📈 Key Learnings

Importance of handling missing values properly

Impact of feature engineering on model performance

Benefits of using Pipeline for clean and reproducible workflows

Comparing multiple models improves performance selection
