Task 1
Label: The repeat_purchase_flag is the label because it is the target variable the model is trying to predict
Data Leakage: The discount_used_on_repeat_order would introduce leakage because it contains information about the repeat purchase that would only be known after the event has already occurred.

Task 2
Exploratory Data Analysis (EDA): This helps you understand distributions and correlations, ensuring the features actually have predictive power and that there aren't hidden biases or outliers in the data.
Data Cleaning and Preprocessing: This step is vital to handle missing values or scale features, as feeding "dirty" or unrefined data into a complex gradient boosting model often leads to poor performance regardless of the algorithm's power.
