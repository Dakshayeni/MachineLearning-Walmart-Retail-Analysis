# Analytics in Retail Sales: A Machine Learning Approach to Enhancing Customer Experience
# Machine Learning in Retail Sales Analysis

## Project Overview
This project focuses on enhancing predictive analytics in retail sales using machine learning techniques. The goal is to accurately forecast sales trends, optimize inventory management, improve marketing strategies, and enhance customer experiences.

## Dataset
The dataset is sourced from Kaggle and contains transactional data from a retail clothing store spanning 2018 to 2022. It includes details such as:
- Transaction Date
- Bill ID
- User ID
- Line Item Amount
- Item Description
- Inventory Category
- Color
- Size
- Zone Name
- Store Name

## Data Preprocessing
Data preprocessing is a crucial step in ensuring the accuracy and efficiency of the models. The following steps were undertaken:
1. **Handling Missing Values** - Missing values were either filled with a default value ('Unknown') or removed selectively.
2. **Removing Duplicates** - Duplicate entries were identified and eliminated.
3. **Extracting Product Names** - A function was used to extract product names from item descriptions.
4. **Handling Inconsistent Data** - Standardization and rectification of mislabeled data entries.
5. **Encoding Categorical Variables** - Label encoding was used for categorical features.
6. **Feature Engineering** - Additional features such as year, month, and day of the week were extracted.

## Data Visualization & Insights
Various visualizations were generated to understand trends and patterns:
- **Total Purchases Made Each Month** - Helps identify peak shopping periods.
- **Average Sales Amount per Month** - Highlights seasonal sales trends.
- **Total Purchases Over the Days of the Week** - Helps understand weekly shopping patterns.
- **Customer Segmentation** - Aids in targeted marketing strategies.

## Machine Learning Models
### 1. **Linear Regression**
- Used to predict future sales trends.
- Achieved an MSE of 2.344 and R² of -0.05684.
- Enhanced using Polynomial Features for better accuracy.

### 2. **K-Means Clustering**
- Used for product categorization based on customer purchase patterns.
- Helped identify groups of products frequently bought together.

### 3. **Artificial Neural Networks (ANNs)**
- Used for predicting future customer purchases based on past behavior.
- Implemented using a Sequential API model with ReLU activation.
- Achieved a high accuracy with minimal Hamming loss.

## Implementation Details
1. **Data Cleaning & Encoding** - Ensuring high-quality data.
2. **Feature Engineering** - Creating new time-based features.
3. **Hyperparameter Tuning** - Using Randomized Search CV to optimize model performance.
4. **Training & Evaluation** - Splitting the dataset into training and test sets for validation.


## Conclusion
This project demonstrates how machine learning can transform retail sales forecasting by providing data-driven insights into purchasing behavior. The use of advanced ML techniques allows retailers to optimize operations, enhance marketing efforts, and improve customer satisfaction.




