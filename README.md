# Online Shoppers Intention Prediction
This project predicts whether an online shopper will make a purchase based on their browsing behavior. 
The dataset used is the https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset
## Dataset
The dataset contains features such as page visits, duration on pages, bounce rates, and more.  
It includes both numeric and categorical variables describing the visitor's behavior on the website.
## Data Preprocessing
- Checked for missing values and handled them appropriately.
- Encoded categorical variables using one-hot encoding.
- Scaled numeric features when necessary.
- Detected and handled outliers in continuous features to improve model performance.  
- Performed feature selection by analyzing correlations and feature importance.
- Split the dataset into training and testing sets (train-test split).
 ## Overview
- **Goal:** Predict whether a visitor will make a purchase.
- **Methods:**
  - Decision Tree Classifier
  - Random Forest Classifier
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC.
