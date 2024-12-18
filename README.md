# Machine-Learning-project-on-Coupon-Recommendation-System-Using-User-Behavior-Data.

# Data cleaning and preprocessing 
This involves preparing raw data for analysis or modeling by improving its quality and structure. First, missing values are addressed by either removing columns/rows with excessive gaps or 
filling them with statistical measures (mean, median, mode). Duplicates are removed to ensure data uniqueness. Categorical data inconsistencies are resolved by standardizing entries. 
Features are encoded into numerical formats using methods like one-hot encoding. Numerical data is scaled using normalization or standardization for consistency.
Import dataset:Read the data from a file (e.g., CSV) into a Data Frame for processing and Identify which columns are categorical (e.g., weather, time) and which are numerical (e.g., 
temperature).

# Exploratory Data Analysis (EDA)
This process of analyzing and visualizing data to uncover patterns, relationships, and insights. It 
involves summarizing data using descriptive statistics (mean, median and variance) and 
visualizations like histograms, scatter plots, and box plots. EDA helps identify trends, anomalies, 
missing values, and correlations, providing a deeper understanding of the dataset.


# Machine learning Model
Difference test was conducted to make predictions, decisions, or 
categorizations without being explicitly programmed for every specific task such as:

# Train Test Split:
This was done to evaluate machine learning models by dividing the dataset into two parts: the training set (70–80%) and the test set (20–30%).The model learns patterns from the training set and is then evaluated on the test set to check its performance on unseen data.

# Logistic Regression:
is a statistical model used for binary classification tasks. It estimates the probability that a given input belongs to a specific class by applying the logistic (sigmoid) function to a linear combination of input features. The output is a value between 0 and 1, representing the predicted probability.

# Decision tree classifier: 
A Decision Tree Classifier is a machine learning model that splits data into branches based on feature conditions, forming a tree-like structure. At each node, it selects the best feature to split data for maximum information gain. The process continues until reaching leaf nodes, which represent the predicted class labels.
# Random Forest model: 
A Random Forest model is an ensemble learning technique that builds multiple decision trees during training. Each tree is trained on a random subset of data and features, and their predictions are combined (via majority voting or averaging) for final output. This approach improves accuracy and reduces overfitting compared to single decision trees.

<img width="501" alt="results" src="https://github.com/user-attachments/assets/b42a5a60-30ec-41e6-8d62-5c684cdefe07">

From the result above,It clearly shows that Random forest model for Y variable 0 and 1 has the superior and best  performance model in comparison with the different models tested. It consistently has the 
highest precision, recall, and F1-Score, making it the most reliable and effective choice among the three models. Random Forest's ensemble approach (using multiple decision trees) 
enhances its ability to generalize, reducing over fitting and ensuring stable performance on unseen data and its ability to maintain strong performance across all metrics for both classes hence making it suitable
# Fine-Tuning and Reporting
The results after fine-tuning the Random Forest model using GridSearchCV show a Train 
Accuracy of 0.655 and a Test Accuracy of 0.64. These values indicate that the model is 
generalizing reasonably well, with a small gap between training and testing accuracy

# Tools used:
Python (scikitlearn,seaborn, matplotlib,Pandas)
