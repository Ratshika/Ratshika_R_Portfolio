## Project 1: Prediction of Customer Churn in Telecom Industry

### Project Overview
- In the Indian Telecom Industry, approximately 80% of revenue comes from the top 20% customers who can be termed as high-value customers. Since the Telecom industry faces  an average of 15-25% annual churn rate, this project was built to help predict the customers who are at high risk of Churn, such that the Company can look into the requirements of the Customer earlier and provide them with offers and benefits in order to retain them.
- Since Prepaid Model is most commonly used in India, Customer churn was predicted based on their usage of Service. The Customer Activity for a span of 3 months was observed and analysed to find Patterns and was used to Predict if the Customer was going to churn or not.
- As the dataset contained a large number of features to predict from, the feature size was reduced using dimensionality reduction technique - **PCA**.
- The dataset was highly imbalanced, as the number of customers churning contributed to only 9% of the entire dataset. This was handled by adding synthetically generated points for the minority class using **SMOTE** technique.
- The final **Classification model** built using **Logistic Regressor** was able to predict **84%** of the customers who intended on churning.
- A **Decision Tree based model** was also built for identifying the top features that led to customers churning.

## Project 2: Identification of Potential Customers from Website Visitors

### Project Overview
- This Project was built to help Companies identify potential Customers who will actually buy their product apart from people just visiting their website.
- A large number of Categorical columns with high variance was present in the dataset, which was handled using appropriate Reduction Techniques and **One-Hot Encoding**.
- Automated Feature Selection was done using **sklearn's RFE**.
- The final model was built using **Logistic Regressor** which was able to assign a score from **0 to 100** to every person visiting the website, based on their potential to turn into a Customer. The Company can then use this score to concentrate more on potential Customers.
- The model built was able to identify 81% of the Potential Customers accurately.

## Project 3: Prediction of Demand for Shared Bikes

### Project Overview
- In India, the Concept of Shared Bikes service through a largely autonomous system is becoming popular and Companies trying to invest in the Concept are looking to understand how the demand for such service varies in each city and what are the factors affecting these demands.
- A **Linear Regressor** model was built which was able to predict **80%** of the bike demands accurately.

## Project 4: Prediction of House Prices in Australia

### Project Overview
- This Project was built to help identify the Important factors/features that determine the price of houses in Australia.
- Ridge and Lasso Regression models were used to predict the price of the houses and around **91%** of the prices were predicted accurately.
- An RMSE ( Root Mean Squared Error) of **0.114** was observed which is pretty low. 
- Hyperparameter tuning was also done for the models to achieve the best possible outcome.

