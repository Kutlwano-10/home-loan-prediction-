This is a standard supervised classification task.A classification problem where we have to predict whether a loan would be approved or not. In a classification problem, we have to predict discrete values based on a given set of independent variable(s).Classification can be of two types:

Supervised: The labels are included in the training data and the goal is to train a model to learn to predict the labels from the features.

Binary Classification : In this classification we have to predict either of the two given classes. For example: classifying the gender as male or female, predicting the result as win or loss, etc.

Multiclass Classification : Here we have to classify the data into three or more classes. For example: classifying a movie's genre as comedy, action or romantic, classify fruits as oranges, apples, or pears, etc.

Loan prediction is a very common real-life problem that each retail bank faces atleast once in its lifetime. If done correctly, it can save a lot of man hours at the end of a retail bank.


For optimization, we incorporated additional features such as Income Sufficiency Ratio (ISR), Disposable Income, Loan-to-Income Ratio (LTI), and Debt-to-Income Ratio (DTI) into our models. These features were designed to enhance predictive performance by providing a more comprehensive financial profile of applicants.

To evaluate the effectiveness of our dataset across different machine learning techniques, we implemented both Boosted Decision Trees (BDT) and Deep Neural Networks (DNN). This allowed us to compare how well the data performs across traditional ensemble methods and deep learning models.

Additionally, we observed that missing values (NaN) in the Credit_History feature were dropped. This decision was made because a NaN value does not indicate whether an applicant has a credit history, making it difficult for the model to determine patterns and relationships within the data. Handling these missing values appropriately is crucial for ensuring model interpretability and improving predictive accuracy.

Logistic Regression model gives : 79% prediction accuracy

Decision Tree model gives : 71% prediction accuracy

Random Forest model gives : 78% prediction accuracy

Random Forest with Grid Search model gives : 77% prediction accuracy

XGBClassifier model gives : 78% prediction accuracy

Boosted Decision Trees model gives : 79% prediction accuracy

Deep Neural Networks model gives : 77% prediction accuracy
