# Loan-Eligibility-Prediction
- The aim of this project is to assess client's historical data in order to come up with a loan eligibility predictor.

# The Dataset
- The dataset contained 614 values with 13 columns.The data contained missing values in 7 variables.

# Dealing with null values
- A histogram was plotted for the ['Applicant Income','Coapplicant Income', 'Total Income' and 'Loan Amount'] columns. They were found to be slightly right skewed. To normalize the data, the log values of the data was obtained which then made the data normalized.
- To deal with the null values, the mode measure of central tendency was applied to the categorical variables
- The numerical data was dealt with using the mean measure of central tendency.

# Analyzing the data
- Individuals with a credit history of 1 are more likely to receive a loan by 68%.
- The males are seen to take out more loans compared to females.
- Married people take out more loans compared to single people.
- As the number of dependents increases, the amount of loan taken reduces.
- Non self-employed people take out more loans compared to self-employed people.

# Loan Prediction
- First off, the data is divided into dependent and independent variables. This is in order to encode the categorical data.
- The data was split into the training and test set at a ration of 80-20.
- For the data to give accurate data, it needs to be scaled.
- Thereafter, different machine learning algorithms are applied to the train data in order to come up with the most appropriate classification method.
- After the different calculations, three methods (Logistic Regression,SVM,Decision Tree) stood out with an accuracy percentage of 83%. They are therefore recommended for use on the test data
