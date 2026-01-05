House Price Prediction Model

I built a house price prediction model using a real-estate dataset and multiple regression techniques to understand the key factors influencing housing prices and to compare how different models perform in terms of accuracy, stability, and interpretability.

Data Preparation

I cleaned and transformed the dataset by handling missing values, encoding categorical variables, and preparing numerical features for modeling. I focused on ensuring data quality and consistency to improve the reliability and performance of the models.

Exploratory Data Analysis (EDA)

I carried out exploratory data analysis to explore relationships between features such as the number of bedrooms, bathrooms, square footage, and house prices. I translated complex statistical patterns into clear, practical insights that could support real-world decision-making.

Modeling Approach

I trained and compared Linear Regression, Ridge Regression, and LASSO Regression models using an 80/20 train–test split. I specifically applied regularization techniques—L2 regularization with Ridge and L1 regularization with LASSO—to reduce overfitting and improve model stability.

Model Evaluation

I evaluated model performance using MAE, MSE, RMSE, and R² metrics. The results showed similar predictive performance across the models, with the regularized models maintaining accuracy while offering better control over coefficient magnitude and stability.

Feature Interpretation

I interpreted the model coefficients to identify key drivers of house prices. The analysis showed that structural features such as the number of bedrooms and bathrooms positively influence house prices, while factors like distance from the city center, house age, crime rate, and noise level have a negative impact on property values.
