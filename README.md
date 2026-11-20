# 🏠 Housing Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analysing and predicting house prices using Machine Learning techniques.

The California Housing Dataset is used to understand how different factors such as median income, location, number of rooms, population, and ocean proximity influence house prices.

A Linear Regression model is developed using Python to predict median house values based on different housing features.

## 🎯 Project Objectives

- Analyse the California Housing Dataset.
- Identify important factors influencing house prices.
- Perform data cleaning and handle missing values.
- Conduct Exploratory Data Analysis (EDA).
- Visualize housing price patterns and relationships.
- Understand the relationship between housing features.
- Build a Machine Learning model using Linear Regression.
- Predict house prices and evaluate model performance.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset Information

**Dataset:** California Housing Dataset

- Total Records: 20,640
- Original Columns: 10
- Target Variable: `median_house_value`

### Dataset Features

| Feature | Description |
|---|---|
| longitude | Geographical longitude |
| latitude | Geographical latitude |
| housing_median_age | Median age of houses |
| total_rooms | Total number of rooms |
| total_bedrooms | Total number of bedrooms |
| population | Population of the area |
| households | Number of households |
| median_income | Median income |
| ocean_proximity | Distance from the ocean |
| median_house_value | Median house price |

## 🔄 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Data Cleaning
5. Missing Value Handling
6. Exploratory Data Analysis (EDA)
7. Data Visualization
8. Correlation Heatmap
9. Data Preprocessing
10. Categorical Encoding
11. Feature Scaling
12. Train-Test Split
13. Linear Regression Model
14. House Price Prediction
15. Model Evaluation
16. Actual vs Predicted Visualization
17. Key Findings
18. Conclusion

## 📊 Exploratory Data Analysis

The following analyses were performed:

- House Price Distribution
- Median Income vs House Price
- Ocean Proximity vs House Price
- House Price Distribution by Ocean Proximity
- Correlation Between Numerical Variables
- Geographical Distribution of House Prices

## ⚙️ Data Preprocessing

The following preprocessing techniques were used:

- Missing values in `total_bedrooms` were replaced with the median.
- Categorical data was converted using One-Hot Encoding.
- Numerical features were standardized using StandardScaler.
- Dataset was divided into 80% training data and 20% testing data.

## 🤖 Machine Learning Algorithm

**Linear Regression**

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project, Linear Regression is used to predict median house prices based on different housing features.

## 📈 Model Evaluation

The model was evaluated using four performance metrics.

| Evaluation Metric | Result |
|---|---:|
| MAE | 50,760.74 |
| MSE | 4,908,476,721.16 |
| RMSE | 70,060.52 |
| R² Score | 0.6254 |

The model achieved an R² score of 0.6254, which means it explains approximately 62.54% of the variation in house prices.

## 💡 Key Findings

1. The dataset contains 20,640 housing records.
2. Median Income has a strong positive correlation (0.688) with Median House Value.
3. House prices vary depending on ocean proximity.
4. Inland areas generally have lower house prices than coastal areas.
5. Island locations have the highest median house prices, but contain very few records.
6. Total Rooms and Total Bedrooms have a strong positive correlation (0.927).
7. Population and Households have a strong positive correlation (0.907).
8. Geographical location plays an important role in house price variations.
9. The Linear Regression model achieved an R² score of 62.54%.

## ⚠️ Limitations

- The dataset contains limited housing information.
- Linear Regression may not capture complex relationships.
- Some important factors affecting house prices are not included.
- Outliers may affect prediction accuracy.
- The model does not explain all variations in house prices.

## 🏁 Conclusion

This project focuses on analysing and predicting house prices using the California Housing Dataset.

Exploratory Data Analysis and data visualization helped identify important factors influencing house prices.

A Linear Regression model was developed and achieved an R² score of 0.6254, explaining approximately 62.54% of the variation in house prices.

Through this project, I gained practical knowledge of Python, Data Analysis, Data Preprocessing, Data Visualization, and Machine Learning techniques.

## ▶️ How to Run This Project

1. Clone or download this repository.
2. Open Jupyter Notebook.
3. Install the required libraries.
4. Place the California Housing Dataset in the appropriate folder.
5. Update the dataset file path in the notebook.
6. Open `machine learning projrct.ipynb`.
7. Run all cells.

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## 👩‍💻 Project Details

- **Project Name:** Housing Price Prediction
- **Domain:** Machine Learning
- **Dataset:** California Housing Dataset
- **Algorithm:** Linear Regression
- **Platform:** Jupyter Notebook
- **Language:** Python
