# Ratshika R

## [Project 1: Style Transfer using CycleGAN](https://github.com/Ratshika/style-transfer-using-GAN)

### Project Overview
- One of the complicated tasks in medical imaging is to diagnose MRI(Magnetic Resonance Imaging). Sometimes to interpret the scan, the radiologist needs different variations of the imaging which can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.
- But to have access to different imaging is difficult and expensive. With the help of deep learning, we can use style transfer to generate artificial MRI images of different contrast levels from existing MRI scans. This will help to provide a better diagnosis with the help of an additional image.
- This project uses **CycleGAN to create T2 weighted MRI scan images from T1 weighted MRI scan images and vice-versa.**
- **Modified U-Net Architechture** was used to build both the **Generator** as well as the **Discriminator.**
- **Data Preprocessing** steps such as ***Data Normalization, Image Resizing and Reshaping, Creating tensor batches*** were performed.
- **Binary Cross-Entropy Loss** was defined for both the Generators and Discriminators, and **Adam** optimizers were used.
- Model generates good translated MRI scan images around **150 Epochs**.

## [Project 2: Melanoma Skin Cancer Detection](https://github.com/Ratshika/melanoma_detection)

### Project Overview
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- The model built can evaluate images and can be used to alert the dermatologists about the presence of melanoma, which has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset used was put together by the **International Skin Imaging Collaboration (ISIC).**
- Data imbalance was handled using the **Augmentor** python package.
- Since the number of images for training was less, Data augmentation techniques such as **Flipping, Random Zoom, Contrast** was done to produce more similar images.
- A custom CNN model was built with around **8 lakh** trainable parameters.
- The model trained after artificial generation of image data had a great improvement in performance, both in training as well as validation dataset.
- Training accuracy of **85%** and Validation accuracy of **80%** was achieved.

## [Project 3: Prediction of Customer Churn in Telecom Industry](https://github.com/Ratshika/telecom_churn_prediction)

### Project Overview
- In the Indian Telecom Industry, approximately 80% of revenue comes from the top 20% customers who can be termed as high-value customers. Since the Telecom industry faces  an average of 15-25% annual churn rate, this project was built to help predict the customers who are at high risk of Churn, such that the Company can look into the requirements of the Customer earlier and provide them with offers and benefits in order to retain them.
- Since Prepaid Model is most commonly used in India, Customer churn was predicted based on their usage of Service. The Customer Activity for a span of 3 months was observed and analysed to find Patterns and was used to Predict if the Customer was going to churn or not.
- As the dataset contained a large number of features to predict from, the feature size was reduced using dimensionality reduction technique - **PCA**.
- The dataset was highly imbalanced, as the number of customers churning contributed to only 9% of the entire dataset. This was handled by adding synthetically generated points for the minority class using **SMOTE** technique.
- The final **Classification model** built using **Logistic Regressor** was able to predict **84%** of the customers who intended on churning.
- A **Decision Tree based model** was also built for identifying the top features that led to customers churning.

## [Project 4: Identification of Potential Customers from Website Visitors](https://github.com/Ratshika/potential_customer_identification)

### Project Overview
- This Project was built to help Companies identify potential Customers who will actually buy their product apart from people just visiting their website.
- A large number of Categorical columns with high variance was present in the dataset, which was handled using appropriate Reduction Techniques and **One-Hot Encoding**.
- Automated Feature Selection was done using **sklearn's RFE**.
- The final model was built using **Logistic Regressor** which was able to assign a score from **0 to 100** to every person visiting the website, based on their potential to turn into a Customer. The Company can then use this score to concentrate more on potential Customers.
- The model built was able to identify 81% of the Potential Customers accurately.

## [Project 5: Prediction of House Prices in Australia](https://github.com/Ratshika/house_price_prediction)

### Project Overview
- This Project was built to help identify the Important factors/features that determine the price of houses in Australia.
- **Ridge** and **Lasso Regression models** were used to predict the price of the houses and around **91%** of the prices were predicted accurately.
- An RMSE ( Root Mean Squared Error) of **0.114** was observed which is pretty low. 
- Hyperparameter tuning was also done for the models to achieve the best possible outcome.

## [Project 6: Prediction of Demand for Shared Bikes](https://github.com/Ratshika/shared_bikes_demand)

### Project Overview
- In India, the Concept of Shared Bikes service through a largely autonomous system is becoming popular and Companies trying to invest in the Concept are looking to understand how the demand for such service varies in each city and what are the factors affecting these demands.
- A **Linear Regressor** model was built which was able to predict **80%** of the bike demands accurately.

