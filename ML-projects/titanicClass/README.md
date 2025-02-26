# Titanic Class Prediction Project  

This project uses Machine Learning to predict the survival of Titanic passengers based on their personal characteristics.  
It leverages the famous Titanic dataset, which includes information such as age, gender, ticket class, and more.  

---

## 📊 Dataset Information:  
- **Main Columns:**  
  - `PassengerId`: Unique ID for each passenger.  
  - `Survived`: Target (0 = Did not survive, 1 = Survived).  
  - `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).  
  - `Name`: Passenger's name.  
  - `Sex`: Gender (male/female).  
  - `Age`: Age of the passenger.  
  - `SibSp`: Number of siblings/spouses aboard.  
  - `Parch`: Number of parents/children aboard.  
  - `Ticket`: Ticket number.  
  - `Fare`: Fare paid for the ticket.  
  - `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).  
  - `male`: Binary column (1 = Male, 0 = Female) created from the `Sex` column.  
  - `Q`: Binary column indicating if the passenger embarked at Queenstown.  
  - `S`: Binary column indicating if the passenger embarked at Southampton.  

---

## 🚀 Objective:  
- To understand the factors influencing survival on the Titanic.  
- To apply Machine Learning techniques such as **Logistic Regression** and **Random Forest**.  

---

## ⚙️ Requirements:  
- Python 3.x  
- Libraries:  
  - `pandas` for data analysis  
  - `numpy` for numerical operations  
  - `scikit-learn` for building models  
  - `matplotlib` and `seaborn` for data visualization  

To install the required libraries, use:  
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
