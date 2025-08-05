# 🏠 Housing Price Prediction

A machine learning project to predict house prices using regression models, leveraging Python libraries such as Scikit-learn, Pandas, and Seaborn.

## 📊 Problem Statement

Predict the selling prices of houses based on various features such as square footage, location, number of bedrooms, etc.

## 📁 Dataset

The dataset is loaded from a CSV file using:

```python
df = pd.read_csv(filepath)
```

## ⚙️ Libraries Used
- Pandas
- Numpy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression,Ridge,Pipeline)

## 🧪 Models Used
- Linear Regression
- Ridge Regression
- Polynomial Features for feature transformation

## 📈 Evaluation Metrics
- R^2 score
- Mean Squared Error (MSE)

## 🔍 Exploratory Data Analysis
- Boxplot to check price variation with waterfront presence
- Regression plot for above-ground square footage vs price

## 🧰 Machine Learning Pipeline
A Scikit-learn Pipeline was used to:
- Standardize features using StandardScaler()
- Create Polynomial Features
- Train models (Linear/Ridge)

## 🧠 Future Improvements
- Try other models: Lasso, Random Forest, XGBoost
- Add feature selection and importance analysis
- Deploy the model as a web app using Flask/Streamlit

## 📬 Contact
Author: Aldous Dsouza
Email: aldous27d.work@outlook.com
LinkedIn: https://www.linkedin.com/in/aldous-dsouza-6a1890352/
