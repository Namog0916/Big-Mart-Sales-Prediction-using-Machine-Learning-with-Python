# Credit Card Fraud Detection Project

![image](https://github.com/Namog0916/Credit-Card-Fraud-Detection-project/assets/126410835/c4badf1f-51a1-4f52-871b-89bea97dec99)

**About the Dataset**:The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Workflow

1.**Import necessary libraries**(e.g., pandas, numpy, scikit-learn, seaborn, matplotlib).

2.**Data Preprocessing:**
Split data into features (X) and target labels (y).

3.**Data Analysis:** * Perform exploratory data analysis (EDA).<br>
* Visualize data distributions and relationships.

5.**Train-Test Split:**
Split data into training and testing sets.

6.**Model Training** (Logistic Regression):
Fit the logistic regression model on the training data.

7.**Evaluate Model:**
Calculate accuracy score using accuracy_score.

8.**Confusion Matrix Visualization:**
* Create a confusion matrix.
* Plot heatmap using seaborn's heatmap.
