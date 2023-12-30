# Predicative-Analytics-Via-Pyspark
## Predicative Analytics of Amazon Product Ratings and Customer Reviews Via PySpark
### Data Overview
* Data Source:  Dr. Julian McAuley Lab at University of California, San Diego
* Original Data: 29 categories , 233 million reviews
* Our Data: 
	- stratified sampling 12200 reviews from 9 categories
 	- around 1400 reviews for each category
	- 4905 unique products
	- time range from 2000 to 2018
### Data Preparation
* Challenges: Dataframe misalignment due to special characters.
  * What we expect:
  ![image](https://github.com/lightbluening/Predicative-Analytics-Via-Pyspark/assets/93415125/38fd7dad-5edf-4fe8-8b83-dc4c0bea8651)
  * What we get:
  ![image](https://github.com/lightbluening/Predicative-Analytics-Via-Pyspark/assets/93415125/fdfb28c9-51ff-47bb-8f1c-2b61d28a5925)



### Methodology 
* Data Cleaning: 
	Check missing values, duplicates, outliers
* Feature Engineering:
	Add new columns(features), sentiment score(Vader), product average rating, to enhance analytical capability.
* Data Exploration
  Exploratory Data Analysis (EDA): Trend Analysis, Drill-down Analysis 
  Correlation Analysis
  Text Analysis
* Machine Learning
  * Data Transformation: One Hot Encoding 
  * Multiclass Classification Models: Logistic Regression, Multiclass Linear SVM, Decision Tree, Naïve Bayes
  * Model Evaluation Metrics: Test Accuracy, Test Precision, Test Recall, Test F1 Score, Confusion Matrix







