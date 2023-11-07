# Loan-Approval-Prediction

When it comes to deciding whether the applicant’s profile is relevant to be granted with loan or not,banks have to look after many aspects.
Predicting loan approval is a common application of machine learning in the financial industry. To create a machine learning model for loan approval prediction, I have  followed  steps below:

1. Data Collection and Preprocessing:
- Gather historical loan data, which should include both approved and denied loans.
- Clean and preprocess the data by handling missing values, encoding categorical variables, and scaling/normalizing numerical features.

2. Exploratory Data Analysis:
- Check the number of rows and columns, data types, and the presence of missing values.
- Examine the distribution of the target variable, which is typically whether a loan was approved or denied. Creating a bar plot or pie chart to visualize the distribution etc.
- Explore the distribution of individual features, both numerical and categorical. Use histograms, box plots, or bar charts to visualize the data. Identify outliers using box plots.
   
3. Data Splitting:
- Split your data into training and testing sets to evaluate your model's performance.

4. Model Selection:
- Choose an appropriate machine learning algorithm. I have used common algorithms for this binary classification problem like  Logistic Regression,  Random Forests, Support Vector Machines and XGBoost.

5. Model Training:
- Train your chosen model on the training data.

6. Model Evaluation :
- To evaluate the model's performance  I have used appropriate metrics, such as accuracy, precision, recall, F1-score. It's important to consider the specific requirements and constraints of  application.
  
7. Hyperparameter Tuning:
- Optimize the model's hyperparameters to improve its performance. This can be done through techniques like grid search or random search. Grid Search method has been applied in this problem.

**Results**: The project achieves an accuracy of around 0.86 using a logistic regression model. Further improvements can be made by feature engineering and exploring different algorithms.

