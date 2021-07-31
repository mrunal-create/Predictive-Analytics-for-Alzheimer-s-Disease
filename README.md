# Predictive-Analytics-for-Alzheimer-s-Disease


Early onset of Alzheimer's Prediction
This project is about predicting early diagnosis of Alzheimer's in patients along with identifying the top 10 and bottom 10 features which can lead to Alzheimer's using feature importance. It explores data cleaning and exploratory data analysis by using techniques like log transformations for skewed target variable to decrease biasness,one hot encoding of categorical variables,filling the missing values using KNN, data balancing using SMOTE as the dataset is imbalanced and is biased and finally scaling. Evaluation of models is done using parameters like auc score,recall,precisoon,accuracy and ROC curve is plotted. classification models like random Forest,Logistic regression and gradient boosting are used and their performances are compared using AUC score,recall,accuracy and precision.
To ensure that model hasnt overfitted the f1-score is calculated for both classes. Cross validation is used to check that model is not overfitting by any chance and hyperparameter tuning is done using Grid Search to pick best parameters for models which can give optimized model.
The best performing model is known to be Logistic Regression giving 0.81 AUC score and 0.88 classification accuracy.
