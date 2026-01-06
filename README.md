# House-Price-Predictor
House Price Predictor is a Machine Learning project that predicts house prices based on key features such as location, size, number of rooms, and other property attributes. The model uses data preprocessing, feature engineering, and regression algorithms to provide accurate price estimates. This project demonstrates end-to-end ML workflow including data analysis, model training, evaluation, and prediction.

### Dataset Source - Bengaluru House price data(KAGGLE)
The dataset contains housing data from Bangalore, including features such as location, total square footage, number of bedrooms (BHK), number of bathrooms, and price. It is used to analyze real estate trends and train a machine learning model to predict house prices based on property characteristics. The dataset requires preprocessing to handle missing values, outliers, and categorical variables.

### Project Description :

In this project, a House Price Prediction model is built using the Bangalore housing dataset. The data is first cleaned by removing irrelevant columns, handling missing values, and converting categorical variables into numerical form using one-hot encoding. Feature engineering is performed, including transforming total square footage and analyzing price per square foot. Outliers are identified and removed to improve model accuracy. The processed data is then split into training and testing sets, and a regression model (Linear Regression) is trained to predict house prices. The model’s performance is evaluated to ensure reliable and realistic price predictions.

&#9733; Dataset Handling Summary:

&#9679; Removed unnecessary features (availability, balcony, area type, society)

&#9679; Handled missing values

&#9679; Converted categorical features like location into numerical format

&#9679; Performed feature engineering and outlier removal

&#9679; Trained and tested a regression model for price prediction.

# Results

&#9733; R2_Score : 0.84
