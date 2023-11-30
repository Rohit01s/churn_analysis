# Churn Chronicles: A ML Odyssey into Customer Churn Analysis

This is the group project which I did with MSc batchmates namely Abhijit Maity, Arpan Saha and Shreyanshi Mishra. The main objective of this ML project was to predict whether the customer churn of Telecom company and propose necessary decisions to reduce the customer churn. The steps involved in this project Includes:

• Importing the main python libraries in the notebook

• Employing the Exploratory Data Analysis involving steps like Data Cleansing, Data Visualizations, Detection of Multicollinearitty and dealing with them, detection of missing values and outliers and dealing with them, Univariate, Bivariate, and multivariate analysis.

• Encoding Categorical features and labels using One-Hot Encoding and Label Encoder.

• Separating Dataset into X and y and then applying Feature Selection on features available, after that we employed splitting of dataset into training and test sets.

• Trained our machine learning algorithms such as logistic regression, K-Nearest Neighbors, Support Vector Machines, Random Forest, Gradient Boost Classifier and XGBoost on training dataset and tested them on testing set.

• We checked the performance of these algorithms via performance metrics like accuracy score, classification report, plot confusion matrix, ROC curve and Precision-Recall Curve.

• We concluded that XGBoost Model was the best ML model in all the models we employed in this classification task with following performance metrices:

Accuracy-81%

Precision (1) - 57% Precision (0) - 84%

Recall (1) - 46% Recall (0) - 89%

True Positive: 158 True Negative: 949 False Positive: 117 False Negative: 183

Area Under Curve (AUC): 81% Precision-Recall Value: 58%

*(1) for people will churn

*(0) for people who will not churn

• After evaluating performance matrices we plotted the feature importances plot to check importances of each features.
