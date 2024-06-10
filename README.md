# Analyzing-insurance-charges
 data science project


Use pandas to load the dataset for easy manipulation and analysis.
Ensure data quality by checking for and handling any null values and duplicates. This dataset has no null values or duplicates.
Use LabelEncoder to transform categorical fields (sex, region, smoker) into numeric values for machine learning algorithms.
Visualize the data distribution using seaborn's displot function to identify any skewness or anomalies.
Examine correlations between features using the corr() function to understand variable relationships. 
Apply feature scaling to ensure all variables contribute equally to the model.
Use metrics such as mean absolute error and root mean squared error to measure model accuracy. 
Test linear regression and use GridSearchCV to optimize parameters for SVM and random forest models.
After evaluating various models, selected the random forest model for its superior performance on this dataset.
