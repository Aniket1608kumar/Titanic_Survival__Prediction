# 🚢 Titanic Survival Prediction (Machine Learning Project)
## ⭐ Project Highlights
- End-to-end ML project (data → model → evaluation)
- Feature engineering improved accuracy from 73% → 82%
- Compared Logistic Regression, Decision Tree, Random Forest
- Identified key survival factors using feature importance

## 📌 Problem Statement
The goal of this project is to predict whether a passenger survived the Titanic disaster using machine learning techniques.

---

## 📁 Project Workflow

1. Data Understanding  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Feature Selection  
6. Model Building  
7. Model Evaluation  
8. Model Improvement  

---

## 📊 Dataset
- Source: Titanic Dataset  
- Target Variable: **Survived**  
- Features include passenger details such as age, gender, class, fare, etc.

---

## 🧹 Data Cleaning
- Handled missing values (Age, Embarked)
- Dropped irrelevant columns (PassengerId, Name, Ticket)
- Converted categorical variables into numeric format

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed survival distribution across gender and class
- Observed higher survival rates for:
  - Females
  - Passengers in higher classes
- Visualized relationships using bar charts and histograms

---

## ⚙️ Feature Engineering
New features were created to improve model performance:

- **FamilySize** = SibSp + Parch  
- **IsAlone** = 1 if passenger is alone, else 0  
- **Sex_Pclass** = Combined feature of gender and class  

These features helped capture hidden patterns in the data.

---

## 🔄 Feature Selection
Selected important features:
- Pclass, Sex, Age, Fare
- FamilySize, IsAlone, Sex_Pclass

Removed:
- PassengerId, Name, Ticket (irrelevant for prediction)

---

## 🤖 Model Building
The following models were trained:

- Logistic Regression  
- Decision Tree  
- Random Forest  

---

## 📈 Model Evaluation

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 78.21%   |
| Decision Tree       | 82.12%   |
| Random Forest       | 82.12%   |

---

## 🌳 Feature Importance
- Fare and Age are the most important features
- Engineered feature **Sex_Pclass** significantly improved performance
- Feature engineering played a key role in boosting accuracy

---

## 🚀 Model Improvement
- Applied feature engineering
- Tuned Decision Tree parameters
- Improved accuracy from ~73% to ~82%

---

## 🧾 Final Conclusion
- Decision Tree and Random Forest performed best (**82% accuracy**)
- Random Forest is preferred due to better generalization
- Feature engineering significantly improved model performance
- Data quality and feature selection are critical in ML projects

---

## 🔮 Future Improvements
- Hyperparameter tuning
- Try advanced models (XGBoost, Gradient Boosting)
- Better handling of missing values

---

## 🛠️ Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📌 Author
- Aniket Kumar
