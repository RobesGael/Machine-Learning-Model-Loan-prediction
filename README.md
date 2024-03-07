# Machine-Learning-Model-Loan-prediction
Like any data science project, it's important to follow certain steps.

### 1- Understanding the problem and defining the goal of the analysis
Context
Financial institutions, like banks and credit unions, face the challenge of accurately assessing the creditworthiness of loan applicants. This decision-making process involves balancing the risk of loan default with the potential for profit and serving the needs of their customers. Traditional methods often rely on manual review and credit scoring models, which can be time-consuming, prone to bias, and limited in their ability to capture complex relationships within the data.

Objectives
Develop a robust and reliable machine learning model to predict whether or not to authorize loan to a customer. This model will be used to:

Improve loan approval efficiency: By automating the initial screening process, the model can help streamline loan applications and reduce the workload on loan officers.
Reduce risk of loan default: By accurately identifying high-risk applicants, the model can help financial institutions make informed lending decisions and minimize potential losses.
Promote financial inclusion: By considering a wider range of factors beyond traditional credit scores, the model can potentially enable institutions to extend credit opportunities to a broader and more diverse pool of applicants.

### 2- Collecting and acquiring data from various sources
Data source: The dataset come from Kaggle. Loan Prediction Problem Dataset (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset?resource=download)
Data format: The dataset is a CSV file and has 614 rows and 13 columns.
Data type: No idea. (It’s important to know if the data along the first-party data, the second-party data, or the third-party data. That could be helpful when dealing with missing values).

### 3- Exploring, cleaning and analysis of the data
Please check out the notebook.

### 4- Building the models

Please check out the notebook.

### 5- Conclusion
Credit_History is a very important variable because of its high correlation with Loan_Status.
The Logistic Regression and Random forest performed well.
The Logistic Regression model has a Good precision : 84 % and very high recall = 98 %, which means that it will not make a lot of false negative and false positive predictions.
What are the ethical implications of the model? What are the consequences of your model making errors? What is the likely effect of the model when it predicts a false negative (i.e., when the model predicts not to authorize the loan to a customer, but we will in fact)? In this case, the company will have a shortfall in terms of turnover
What is the likely effect of the model when it predicts a false positive (i.e., when the model predicts to authorize the loan to a customer, but we won't actually do that)? The company can take proactive steps to get customers to pay for their loans.
##### Check out Insight files for the summary report

### Informations:
Name: Robes Fokoueng
