# 🛍️ Myntra Discount Prediction
This project focuses on predicting the best discount to offer on Myntra products using machine learning techniques. The dataset includes over 526,000 rows with product-level details such as product category, brand, ratings, and existing discount offers.

##### =============================================================================================== 

##### 🔍 Why This Project?
I chose this dataset because of its scale and real-world complexity. With more than 526,000 rows, it mimics real-time e-commerce data. Additionally, the dataset was highly unstructured and noisy, making it a perfect candidate to test my data cleaning and modeling skills.

##### =============================================================================================== 

##### 🎯 Problem Statement
Deciding what discount amount to offer for maximizing sales while maintaining profitability is a common challenge in e-commerce. This project aims to build a regression model that automates discount prediction based on product features.

##### =============================================================================================== 

##### 🛠️ Workflow & Key Steps
##### • Extracted and loaded the dataset from a zipped file.
##### • Performed an initial column analysis and removed features that added little to no value.
##### • Cleaned complex unstructured data such as DiscountOffer, which contained inconsistent formats like “10% off” or “flat ₹500 off”. These were converted to numerical values in a new column DiscountPrice.
##### • Created 3 new features based on domain understanding to enhance prediction power.
##### • Split the data into training and testing sets to prevent data leakage.
##### • Conducted EDA: Univariate, Bivariate, and Multivariate analysis.
##### • Encoded categorical features appropriately.
##### • Trained and evaluated 4 regression models: Random Forest, Gradient Boosting, XGBoost, and Linear Regression.
##### • Identified Random Forest as the best-performing model.

##### =============================================================================================== 

##### ⚠️ Challenges Faced
##### • Due to the large size of the dataset, applying techniques like K-Fold Cross Validation and GridSearchCV was computationally expensive.
##### • Even basic model training took significant time, requiring careful memory and time management.

##### =============================================================================================== 

##### 📊 Final Results
##### • Random Forest Regressor outperformed all others:

##### MAE: 0.12
##### MSE: 0.07
##### R² Score: 0.93

