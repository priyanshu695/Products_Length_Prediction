# Products_Length_Prediction
Machine Learning Model to Predict Product Length

The goal is to develop a machine learning model that can predict the length dimension of a product. Product length is crucial for packaging and storing products efficiently in the warehouse. Moreover, in many cases, it is an important attribute that customers use to assess the product size before purchasing. However, measuring the length of a product manually can be time-consuming and error-prone, especially for large catalogs with millions of products.

The prediction is done by using Ridge Regression

# Evaluation metric
score = max( 0 , 100*(1-metrics.mean_absolute_percentage_error(actual,predicted)))
