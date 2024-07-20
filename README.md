PROBLEM STATEMENT : If a relationship will be successful or not with respect to various factors such as 'Medium of Usage', 'Name of Universities', 'Answer to : Do you use tinder ?', 'Count of Tinder Match', 'Percentage of Tinder Match'.

1. Data Cleaning and Preprocessing:
o Handling Missing Values: We employed various strategies such as imputation and removal of rows/columns with excessive missing values.
o Normalizing Numerical Features: We normalized them using techniques such as Min-Max Scaling.
o Encoding Categorical Variables: Categorical variables, such as university names and user responses, were encoded using one-hot encoding and label encoding to facilitate their use in machine learning models.

2. Exploratory Data Analysis (EDA):
o Data Visualization: We used histograms, box plots, and scatter plots to visualize the distribution of numerical variables and identify any outliers or anomalies.
o Correlation Analysis: By examining the correlations between variables, we identified potential predictors of relationship success. For instance, we observed that higher match counts and percentages were positively correlated with successful relationships.
o Feature Engineering: Based on our findings, we created new features that could enhance model performance. For example, we derived a feature representing the ratio of matches to total swipes.

4. Model Development:

o Logistic Regression: A popular and interpretable model, logistic regression served as our baseline model. It provided a reasonable accuracy but was outperformed by other models.
o K-Nearest Neighbors (KNN): KNN emerged as the best-performing model, achieving an accuracy score of 82.4%. This model leverages the similarity between data points to make predictions, making it particularly suitable for our dataset.
o Linear Discriminant Analysis (LDA): Although LDA did not perform as well as KNN, it provided valuable insights into the linear separability of the classes in our data.
