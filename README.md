# Predicative-Analytics-Via-Pyspark
## Predicative Analytics of Amazon Product Ratings and Customer Reviews Via PySpark
### Data Overview
Data Source:  Dr. Julian McAuley Lab at University of California, San Diego
Original Data: 29 categories , 233 million reviews
Our Data: 
	- stratified sampling 12200 reviews from 9 categories
 	- around 1400 reviews for each category
	- 4905 unique products
	- time range from 2000 to 2018
### Data Preparation
<img width="1049" alt="image" src="https://github.com/lightbluening/Predicative-Analytics-Via-Pyspark/assets/93415125/7f2395a3-e17e-415f-8e10-adf5ce8855c5">
<img width="1108" alt="image" src="https://github.com/lightbluening/Predicative-Analytics-Via-Pyspark/assets/93415125/dbd0e174-6c42-4fcd-93b0-8366de6d1c1a">

### Methodology 
Data Cleaning: 
	Check missing values, duplicates, outliers
Feature Engineering:
	Add new columns(features), sentiment score(Vader), product average rating, to enhance analytical capability.
Data Exploration
  Exploratory Data Analysis (EDA): Trend Analysis, Drill-down Analysis 
  Correlation Analysis
  Text Analysis
Machine Learning
  Data Transformation: One Hot Encoding 
  Multiclass Classification Models: Logistic Regression, Multiclass Linear SVM, Decision Tree, Naïve Bayes
  Model Evaluation Metrics: Test Accuracy, Test Precision, Test Recall, Test F1 Score, Confusion Matrix







