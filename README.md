This is a standard supervised classification task where we predict whether a loan will be approved or not, a binary classification problem involving discrete predictions based on independent variables. In supervised learning, the training data includes labels, enabling the model to learn and predict outcomes. For loan prediction—a common challenge in retail banking—we enhanced our models by incorporating features like Income Sufficiency Ratio (ISR), Disposable Income, Loan-to-Income Ratio (LTI), and Debt-to-Income Ratio (DTI) to improve predictive performance. 
We evaluated the dataset using both Boosted Decision Trees (BDT) and Deep Neural Networks (DNN) to compare traditional ensemble methods with deep learning approaches. Additionally, missing values in the Credit_History feature were removed due to their ambiguity, ensuring better model interpretability and accuracy. Proper handling of such missing data is critical for effective pattern recognition and reliable predictions.

Logistic Regression model gives : 79% prediction accuracy

Decision Tree model gives : 71% prediction accuracy

Random Forest model gives : 78% prediction accuracy

Random Forest with Grid Search model gives : 77% prediction accuracy

XGBClassifier model gives : 78% prediction accuracy

Boosted Decision Trees model gives : 79% prediction accuracy

Deep Neural Networks model gives : 77% prediction accuracy
Acknowledgements: I thank Phodiso Maroeshe (https://github.com/phodiso-7?tab=repositories) for his insightful discussions and his contribution in optimising our models.
