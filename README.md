# 🌊 Titanic Dataset - Machine Learning Pipeline 🛠️

## ✨ Project Overview
This project demonstrates how to build a **Machine Learning Pipeline** for the **Titanic Dataset** using **Decision Tree Classifier**. The pipeline includes:

- **Data Preprocessing** (handling missing values, encoding, and scaling)
- **Feature Selection** using **SelectKBest**
- **Model Training** with **Decision Tree Classifier**
- **Pipeline Serialization** using **Pickle**

## 📊 Data Preprocessing
- **Handling Missing Values**: `SimpleImputer()`
- **Encoding Categorical Features**: `OneHotEncoder()`
- **Feature Scaling**: `MinMaxScaler()`
- **Feature Selection**: `SelectKBest(score_func=chi2, k=8)`

## 🧠 Model Training
- **Algorithm**: `DecisionTreeClassifier()`
- **Pipeline**: Created with `ColumnTransformer` and `Pipeline`
- **Serialization**: Saved using **Pickle**  
