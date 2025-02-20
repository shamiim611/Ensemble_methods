# Ensemble_methods
Data Background
The credit dataset contains 1,000 loan examples, with a mix of numeric and categorical features describing the loan details and the characteristics of the applicants. The dataset includes a class variable that indicates whether a loan went into default.
________________________________________
Steps to Follow:
1.	Data Preprocessing:
Apply label encoding to both predictor and target variables.
Split the dataset into training and testing sets.
2.	Building the Model:
Construct a decision tree model using the credit dataset.
3.	Cross-Validation:
Perform cross-validation to ensure reliable predictions from the model.
4.	Enhancing Model Performance:
Improve the model using ensemble methods such as:
	Bagging
	Boosting
	Random Forest
5.	Parameter Tuning:
Use Grid Search to fine-tune the hyperparameters for optimal performance.
6.	Model Evaluation:
Evaluate each model’s performance using the ROC curve and AUC (Area Under the Curve).
Key Skills Demonstrated:
1.	Data preprocessing (label encoding, train-test split).
2.	Building and fine-tuning decision tree models.
3.	Using ensemble methods to improve model accuracy.
4.	Evaluating and interpreting model performance with metrics like ROC and AUC.
Tools Required:
•	Pandas: For data preprocessing and manipulation.
•	Scikit-learn: For building decision tree models, ensemble methods, and evaluating model performance.


CONCLUSION:
   our baselearner(decision tree) was overfitting and it is also a strong learner(max_depth = 19).
  	this could explain why ensemble methods that reduce variance(random forest,bagging) performed better than adaboost(works better with weak learners.
  	gradient boosting is often best for strong learners
