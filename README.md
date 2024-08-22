# Linear Regression on Boston Housing Dataset

## Overview
This project applies linear regression analysis to predict housing prices based on various features from the Boston Housing dataset. The objective is to develop a predictive model that estimates housing prices by analyzing features such as the number of rooms, crime rate, and distance to employment centers, among others.

## Dataset
The dataset used in this project is the Boston Housing dataset, a well-known dataset used for regression analysis. It includes 506 observations of 14 variables (features) related to housing in the Boston area.

### Features
- **CRIM**: Per capita crime rate by town
- **ZN**: Proportion of residential land zoned for lots over 25,000 sq. ft.
- **INDUS**: Proportion of non-retail business acres per town
- **CHAS**: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **NOX**: Nitric oxide concentration (parts per 10 million)
- **RM**: Average number of rooms per dwelling
- **AGE**: Proportion of owner-occupied units built before 1940
- **DIS**: Weighted distance to five Boston employment centers
- **RAD**: Index of accessibility to radial highways
- **TAX**: Full-value property tax rate per $10,000
- **PTRATIO**: Pupil-teacher ratio by town
- **B**: Proportion of Black residents by town
- **LSTAT**: Percentage of lower status of the population
- **MEDV**: Median value of owner-occupied homes (dependent variable)

## Steps Involved
1. **Data Preprocessing**: Handle missing values, normalize features, and check for multicollinearity.
2. **Exploratory Data Analysis (EDA)**: Analyze the distribution of variables, correlations, and outliers.
3. **Model Building**: Fit a linear regression model using the features to predict the median house price (`MEDV`).
4. **Model Evaluation**: Evaluate model performance using metrics such as Mean Squared Error (MSE), R-squared, and visualizations like residual plots and predictions vs actuals.
5. **Interpretation of Results**: Analyze the significance of features and the model's ability to generalize to unseen data.

## Results
- **R-squared**: Indicates how well the independent variables explain the variance in the dependent variable.
- **MSE**: Measures the average squared difference between predicted and actual values, giving insight into the prediction error.

## Prerequisites
- **Python 3.x**
- **Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   ```
2. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the `linear_regression_boston.ipynb` notebook in Jupyter or Google Colab.

## Conclusion
This project demonstrates how to apply linear regression to predict housing prices using the Boston Housing dataset. The analysis includes model building, evaluation, and insights into the relationships between various features and housing prices.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
