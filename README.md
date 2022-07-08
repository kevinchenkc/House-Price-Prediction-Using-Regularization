## Boston House Price Prediction with Regularization (Ridge/Lasso/ElasticNet + Tuning)

Dataset source: [Kaggle.com](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices)

## Machine Learning Methodology
1. Domain Knowledge - Business Knowledge
    - Define business problem / problem statement
    - Define goals
    - Define business questions
    - Data collection
    - Describe features & target (data)

2. Data Wrangling and Data Exploration
    - Check data types
    - Describe data (numeric-categoric)
    - Check (NaN, ?, unknown, ' ', etc) and handle (dropna or fillna) missing value 
    - Check and handle (drop,keep,transform) outliers
    - Check duplicates data

3. Data Analysis and Data Visualization
    - Data Analysis
        - Bivariate/Multivariate analysis -> Crosstab, Groupby, Pivot Table
        - Insight
    - Data Visualization
        - Multivariate analysis
        - Insight
    
4. **`Machine Learning`**
    - Data Preparation
        - Feature Engineering
            - Correlation Test
            - Domain Knowledge based on EDA
            - Polynomial Features
            - Regularization with Ridge/Lasso/ElasticNet + Manual Tuning
        - Feature Selection
            - Splitting Data
            - Training Model -> Base Model (.fit())
            - Error analysis with regression
            - Evaluation Matrix Comparison (Base Model vs After Polynomial Features)
    - Conclusion
