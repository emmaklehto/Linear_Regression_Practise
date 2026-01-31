# Linear Regression on US Housing Prices

This repository demonstrates a **linear regression model** applied to the US Housing dataset. The notebook explores the dataset, performs data analysis, fits a linear regression model, evaluates it, and interprets the results.


## Dataset

- **Filename:** `USA_Housing.csv`  
- **Samples:** 5000  
- **Features:** 7 numerical features + Address  
- **Source:** [Kaggle - USA Housing](https://www.kaggle.com/datasets/aharless/usa-housing)

The goal is to **predict housing prices** based on numerical features like income, house age, and number of rooms.



## Notebook

- **Linear_Regression_Practise.ipynb**  
  This notebook includes:
  - Dataset exploration and visualization
  - Feature selection
  - Train-test split
  - Linear regression model training
  - Coefficient analysis (standard errors, t-statistics)
  - Model evaluation (MAE, MSE, RMSE, R²)
  - Residual analysis
  - Insights and interpretation



## My Contributions

Although the notebook started as a base template from the course, my work includes:

- Performing the **train-test split**  
- **Fitting the linear regression model** and checking intercepts & coefficients  
- Calculating **standard errors and t-statistics**  
- Performing **predictions and evaluating errors**  
- Adding **visualizations and commentary** on correlations, predicted vs actual, and residuals  
- Writing **insights and conclusions**



## Requirements

Install the required Python packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
