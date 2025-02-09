# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset**. The dataset contains information about passengers on the Titanic, including their **age, gender, ticket class, fare, survival status, and more**. Through this analysis, we aim to uncover patterns, trends, and insights into survival rates and influencing factors.

## 📂 Dataset Information
The Titanic dataset is available from **Kaggle** and consists of the following key features:
- **Survived**: 0 = No, 1 = Yes
- **Pclass**: Ticket class (1st, 2nd, 3rd)
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 🛠️ Libraries Used
This project utilizes the following Python libraries:
- `pandas` → Data manipulation and analysis
- `numpy` → Numerical computations
- `matplotlib` → Data visualization
- `seaborn` → Statistical data visualization

## 🔍 Exploratory Data Analysis (EDA) Steps
1. **Load the dataset**: Read the Titanic dataset using Pandas.
2. **Data Cleaning**: Handle missing values, incorrect data types, and outliers.
3. **Descriptive Statistics**: Understand data distributions using `.describe()` and `.info()`.
4. **Visualization**:
   - **Histogram** of age distribution
   - **Bar charts** for survival rates across gender and ticket class
   - **Box plots** for fare distribution by class
   - **Correlation heatmap** for feature relationships
5. **Feature Engineering**: Creating new meaningful features from existing ones.
6. **Key Insights & Findings**: Summarizing trends and patterns found in the dataset.


## 📈 Key Insights
- **Women had a higher survival rate than men**.
- **First-class passengers had a much higher survival rate compared to third-class passengers**.
- **Younger passengers had better survival chances than older ones**.
- **Fare prices were significantly higher for first-class passengers**.

## 🎯 Future Work
- Apply **machine learning models** to predict survival.
- Perform **advanced feature engineering** to enhance insights.
- Conduct **more detailed statistical analysis** on survival factors.

## 📜 References
- Kaggle Titanic Dataset: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- Pandas Documentation: [https://pandas.pydata.org/](https://pandas.pydata.org/)
- Seaborn Documentation: [https://seaborn.pydata.org/](https://seaborn.pydata.org/)

## 🤝 Contributing
Feel free to contribute by suggesting improvements, reporting issues, or adding new analysis techniques!

---
### 🚀 Happy Analyzing! 🎯

