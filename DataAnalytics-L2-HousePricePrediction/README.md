# House Price Prediction Using Linear Regression

## 1. Introduction

House price prediction is an important application of data analytics and machine learning. Property prices are influenced by several factors, including the size of the house, number of rooms, available facilities and furnishing condition.

The objective of this project is to develop a Linear Regression model that predicts house prices based on various housing features.

This project follows an end-to-end machine learning workflow, including data exploration, preprocessing, feature selection, model training, evaluation and interpretation.

## 2. Dataset Description

- **Dataset:** Housing.csv
- **Total Records:** 545
- **Total Columns:** 13
- **Input Features:** 12
- **Target Variable:** `price`
- **Data Types:** Numerical and categorical

The dataset includes features such as area, bedrooms, bathrooms, stories, parking, main road access, air conditioning and furnishing status.

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 4. Project Workflow

1. Loaded and explored the housing dataset.
2. Checked missing values and duplicate records.
3. Analysed the distribution of house prices.
4. Selected relevant features for prediction.
5. Performed correlation analysis using a heatmap.
6. Converted categorical variables using One-Hot Encoding.
7. Split the dataset into 80% training and 20% testing data.
8. Built a Linear Regression model.
9. Evaluated model performance using MSE, RMSE and R².
10. Visualised actual versus predicted prices.
11. Analysed residuals and model coefficients.

## 5. Data Preprocessing

- No missing values were found.
- No duplicate records were identified.
- Categorical features were transformed using One-Hot Encoding.
- The dataset was divided into training and testing sets using an 80:20 ratio.

## 6. Model Building

A Linear Regression model was developed using Scikit-learn.

The model was trained using 80% of the dataset and evaluated on the remaining 20%.

## 7. Model Evaluation Results

| Evaluation Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | 1,754,318,687,330.70 |
| Root Mean Squared Error (RMSE) | 1,324,506.96 |
| R-squared (R²) | 0.6529 |

The model achieved an R² score of **0.6529**, explaining approximately 65.29% of the variation in house prices.

## 8. Key Findings

- Area and bathrooms show relatively strong positive correlations with house prices.
- Bathrooms have the highest positive regression coefficient.
- Air conditioning and preferred-area status also show positive coefficients.
- Unfurnished status has the strongest negative coefficient among the categorical features.
- Prediction errors become more spread out at higher predicted prices.

## 9. Limitations

- The dataset does not contain detailed geographical location or house-age information.
- The model shows limitations in predicting higher-priced properties.
- The residual analysis suggests non-constant error variance.
- Linear Regression may not capture all complex relationships between housing features and prices.

## 10. Conclusion

This project demonstrates the application of Linear Regression for house price prediction through an end-to-end machine learning workflow.

The model achieved an R² score of 0.6529. Data visualisations and coefficient analysis helped evaluate prediction performance and understand the relationships between housing features and predicted prices.

Although the model provides a useful baseline, incorporating additional features and exploring advanced algorithms could improve prediction accuracy.

## 11. Project Files

- `OIBSIP_L2_Task1_House_Price_Prediction.ipynb` – Jupyter Notebook containing the complete analysis and model.
- `Housing.csv` – Dataset used for the project.
- `README.md` – Project documentation.

## 12. How to Run

1. Open the Jupyter Notebook using Google Colab or Jupyter Notebook.
2. Install the required Python libraries if they are not already available.
3. Ensure the dataset is accessible at the location specified in the notebook.
4. Run all notebook cells in order to reproduce the analysis and results.
