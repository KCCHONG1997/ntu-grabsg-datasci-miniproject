
# SC1015 (FCS1) Data Science Mini Project GrabFood Data Analysis

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focus on 
[Kaggle | Grab Restaurant in Singapore](https://www.kaggle.com/datasets/polartech/16000-grab-restaurants-in-singapore)

## Table of Content
1. [Data Cleaning](./Data%20Cleaning.ipynb)
2. [Data Exploratory/Analysis/Visualization](./Data%20Analysis.ipynb)


## Contributors
- @KCCHONG1997 - Cleaning Data, Data Visualization, Managing github repo and Data Analysis
- @meiyeedope - Cleaning Data, Data Visualization and Data Analysis (Finding correlation and assist in building model)
- @kaibin157 - Cleaning Data, Data Visualization and assist in Data Analysis

## Problem Statement
- How can we optimise/improve grab services from this datasets?

## Models Used
- **Linear Regression**: Applied to predict 'weighted_rating' from features such as 'delivery_time' and 'total opening time hours', with evaluation using MSE and R².

- **Ridge and Lasso Regression**: Utilized to address potential overfitting and multicollinearity, with models tested across various alpha values to assess impact on performance.

- **Exploratory Data Analysis (EDA)**: Included scatter plots and boxplots to visualize and understand the data relationships and distribution.

- **Outlier Handling**: Identification and removal of outliers to improve model accuracy, particularly for features like 'delivery_time'.

- **One-Hot Encoding**: Transformed categorical variables like 'loc_type' and 'delivery_options' for regression analysis.

- **ANOVA Tests**: Conducted to examine the differences in 'weighted_rating' across categories such as 'delivery_options'.

- **Correlation Analysis**: Performed to determine the strength and direction of relationships between variables.

These methods collectively contributed to a comprehensive data-driven approach to analyze and optimize Grab's services.

## What did we learn from this project?
- ANOVA technique
- Ridge and Lasso
- Data representation like heatmap on map
- Other packages: json, statsmodels.api, OneHotEncoder
- Collaborating using GitHub

## References
- [Ridge and Lasso Tutorial](https://www.analyticsvidhya.com/blog/2016/01/ridge-lasso-regression-python-complete-tutorial/)
- [ANOVA for Multiple Linear Regression](http://www.stat.yale.edu/Courses/1997-98/101/anovareg.htm)
- [OneHotEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
- [GeeksforGeeks - OneHotEncodere](https://www.geeksforgeeks.org/ml-one-hot-encoding/)
- [OpenStreetMap - Heatmap](https://plotly.com/python/mapbox-density-heatmaps/)