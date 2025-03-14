# Titanic-Survival-Prediction
This project predicts whether a passenger on the Titanic survived or not using a logistic regression model.  

---

## 🚀 **Project Overview**
- This project is based on the Titanic dataset.  
- The goal is to predict passenger survival using machine learning.  
- The model is built using Python and Scikit-learn.  

---

## 📌 **Dataset Details**  
- **Dataset:** test.csv and train.csv  
- **Columns Used:**  
  - `Pclass` – Passenger class  
  - `Sex` – Gender  
  - `Age` – Age of passenger  
  - `SibSp` – Number of siblings/spouses aboard  
  - `Parch` – Number of parents/children aboard  
  - `Fare` – Fare paid  
  - `Embarked` – Port of embarkation  

---

## 🔨 **Libraries Used**  
- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  

---

## 🏆 **Steps Followed**  
1. Data Cleaning  
   - Filled missing `Age` values with the median  
   - Filled missing `Embarked` values with the mode  
2. Data Visualization  
   - Count plots for `Pclass` and `Survived`  
3. Feature Selection  
   - Removed irrelevant columns (`PassengerId`, `Name`, `Ticket`)  
4. Model Training  
   - Used Logistic Regression  
5. Model Evaluation  
   - Calculated training data accuracy  

---



