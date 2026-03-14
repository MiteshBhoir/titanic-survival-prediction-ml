# Titanic Survival Prediction using Machine Learning

This project demonstrates how different Machine Learning classification algorithms can be used to predict passenger survival using the Titanic dataset.

The project was implemented using Python in Google Colab and includes the complete Machine Learning workflow from data preprocessing to model evaluation.

---

## Project Overview

In this project, I explored how multiple classification algorithms perform on the same dataset.

The goal is to predict whether a passenger survived the Titanic disaster based on available features.

---

## Dataset

The dataset used in this project is the Titanic dataset available in the Seaborn library.

Features in the dataset include:

- Passenger Class
- Age
- Gender
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Fare
- Port of embarkation
- Survival status

---

## Machine Learning Workflow

### 1. Data Loading
The dataset is loaded using the Seaborn library.

### 2. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Filled missing age values using the mean
- Removed rows with missing embarked values

### 3. Data Preprocessing
- Converted categorical features into numerical values using LabelEncoder
- Applied StandardScaler for feature scaling

### 4. Train-Test Split
The dataset was divided into:

- 80% training data
- 20% testing data

---

## Machine Learning Models Implemented

The following classification algorithms were applied:

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Naive Bayes  
4. Decision Tree  
5. Support Vector Machine (SVM)

---

## Model Evaluation

Models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

Additionally, **5-Fold Cross Validation** was used to evaluate model performance.

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

---

## Repository Structure
```
titanic-survival-prediction-ml
│
├── titanic_ml.ipynb
├── README.md 

```
---
## Running the Project

You can run this project directly using Google Colab.

1. Open the notebook file `titanic_ml.ipynb`
2. Upload it to Google Colab
3. Run the cells step-by-step

---

## Learning Outcome

Through this project I learned:

- Data preprocessing techniques
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Training multiple Machine Learning models
- Evaluating classification algorithms
- Using cross validation

---

## Author

Mitesh Bhoir  
Computer Engineering Student  
Full Stack Developer | Learning Machine Learning

GitHub: https://github.com/MiteshBhoir/titanic-survival-prediction-ml.git
