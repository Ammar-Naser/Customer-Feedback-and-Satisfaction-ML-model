# Customer-Feedback-and-Satisfaction-ML-Model

In this project, I trained an ML model to classify the Customer Feedback. If the Satisfaction level (0-25) it’s Very Low, (25-50 score) it’s Low, (50-75) it’s Medium, (75-100) it’s High. I used 4 ML algorithms and an ANN algorithm to train this model, and compared their accuracy to save the best model.

**Dataset description: 
The Customer Feedback and Satisfaction Dataset is a synthetic dataset designed to analyze and predict customer satisfaction based on various demographic and behavioral factors. It contains data for 38,444 customers, capturing their feedback on products and services in a structured format.

**Features:
CustomerID: Unique identifier for each customer.
Age: Age of the customer (numerical).
Gender: Gender of the customer (categorical: Male, Female).
Country: Country of residence (categorical: USA, Canada, UK, Germany, France).
Income: Annual income of the customer (numerical).
ProductQuality: Quality rating of the product on a scale from 1 to 10 (numerical).
ServiceQuality: Quality rating of the service on a scale from 1 to 10 (numerical).
PurchaseFrequency: Number of purchases made by the customer in the last year (numerical).
FeedbackScore: Overall feedback score categorized as Low, Medium, or High (categorical).
LoyaltyLevel: Loyalty status of the customer (categorical: Bronze, Silver, Gold).
SatisfactionScore: Target variable representing customer satisfaction as a percentage between 1 and 100 (numerical).

**What I do in this project:
- Data cleaning. 
- EDA, Visualization.  
- Used YData profiling.
---------------
Feature Engineering: 
- Correlation between Features. 
- Feature selection. 
- Feature Extraction.
- Feature Expansion(polynomial Features). 
- Dimensionality reduction (PCA).
--------------
- Used 4 ML algorithms and 1 ANN algorithm.
---------------
Model Evaluation: 
- Compared the models to get the best model.
- Saved the best model.
