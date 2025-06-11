# 💊 Drug Classification Using Decision Tree Classifier

## 📌 Overview
This repository contains a machine learning project that classifies **drug types** based on patient health attributes using a **Decision Tree Classifier**. This classification helps in recommending suitable medications based on individual patient profiles. 🏥

## 📊 Dataset
The dataset includes the following health attributes:

| Feature | Description |
|---------|------------|
| 🕰 **Age** | Patient's age |
| 🚻 **Sex** | Gender (Male/Female) |
| 🩸 **BP** | Blood Pressure level (categorical: High, Normal, Low) |
| 🍽 **Cholesterol** | Cholesterol level (categorical: High, Normal) |
| ⚡ **Na_to_K** | Sodium-Potassium ratio in blood |
| 💊 **Drug** | Prescribed drug type (target variable) |

## 🛠 Dependencies
Install the required libraries before running the project:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🏗 Model Training
The classification process follows these key steps:
1. 🧹 **Data Preprocessing** – Handling missing values, encoding categorical variables, and scaling features.
2. 🔍 **Exploratory Data Analysis (EDA)** – Understanding feature distributions and relationships.
3. 🌳 **Decision Tree Classifier** – Training a model to classify drugs based on patient attributes.
4. 📊 **Evaluation Metrics** – Assessing accuracy, precision, recall, and confusion matrix.

## 📈 Results
The trained model predicts drug types based on patient health data, improving medical recommendations. 🏥

Key results:
- ✅ **Decision Tree structure visualization**
- 🔍 **Feature importance analysis**
- 📊 **Classification accuracy and confusion matrix**

## 🔮 Future Improvements
Possible enhancements:
- 🛠 **Hyperparameter tuning** for better model performance
- 🏆 **Exploring alternative classification models** (e.g., Random Forest, SVM)
- 📡 **Integrating real-time patient data for dynamic drug recommendations**

## 💡 Contributing
Feel free to fork the repository and submit pull requests with improvements. 🚀
