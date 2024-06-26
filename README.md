# Predictive-Analytics
There are two experiential learning assignments in this repository

Problem Statement for the first experiential assignment:
The following dataset credit.csv contains information about credit card debt for hundreds of customers. The response is balance (average credit card debt for each individual) and there are several quantitative predictors: age, cards (number of credit cards), education (years of education), income (in thousands of dollars), limit (credit limit), and rating (credit rating). You need carry out detailed Exploratory Data Analysis, create linear regression models based on the techniques you have learnt in the course and carry out detailed outlier and residual analysis. Also, comment on the bias variance trade off, that is, overfitting and under fitting aspect of the model created.
https://drive.google.com/file/d/1Ga7Q25CTCR7EFYmdlR2JEr6m6ptcS_sk/view?usp=sharing
Income - income in thousands of dollars
Limit - credit limit
Rating - credit rating
Cards - number of credit cards
Age - Age of the customer
Education - years of education
Own - house ownership
Student - student status
Married - marital status
Region - East, West or South
Balance - average credit card debt for each individual

In this assignment, you are expected to carry out data exploration, extensive model selection process, model diagnostics and testing etc. A Machine Learning project is generally not linear but will consist broadly of the following major steps.
Define Problem
Prepare Data
Data understanding (EDA)
Model building
Evaluate
Improve Model
Report Results


Problem Statement Number 2 : 
MCA Technology Solutions Private Limited was established in 2015 in Bangalore with an objective to integrate analytics and technology with business. MCA Technology Solutions helped its clients in areas such as customer intelligence, forecasting, optimization, risk assessment, web analytics, and text mining, and cloud solutions. Risk assessment vertical at MCA technology solutions focuses on problems such as fraud detection and credit scoring. Sachin Kumar, Director at MCA Technology Solutions, Bangalore was approached by one of his clients, a commercial bank, to assist them in detecting earning manipulators among the bank’s customers. The bank provided business loans to small and medium enterprises and the value of loan ranged from INR 10 million to 500 million ($1 = INR 66.82, August 16, 2016). The bank suspected that their customers may be involved in earnings’ manipulations to increase their chance
of securing a loan.
Saurabh Rishi, the Chief Data Scientist at MCA Technologies, was assigned the task of developing a use case for predicting earning manipulations. He was aware of models such as Beneish model that was used for predicting earning manipulations; however, he was not sure of its performance, especially in the Indian context. Saurabh decided to develop his own model for predicting earning manipulations using data downloaded from the Prowess database maintained by the Centre of Monitoring Indian Economy (CMIE). Daniel received information related to earning manipulators from Securities Exchange Board of India (SEBI) and the Lexis Nexis database. Data on 220 companies was collected to develop the model.
The data is available in the file “Earnings Manipulation 220.csv” in the following link.
https://drive.google.com/file/d/1h-qteu-obJ5y5nQhHn_ypUOzZSp8lEVn/view?usp=sharing
Description of the columns is given in the following Table. In this table
 netPPE is net Property, Plant, and Equipment. Property Plant and Equipment is the value of all buildings, land, furniture, and other physical capital that a business has purchased to run a business.
 Subscript (t) means value in the current year financial statement and subscript (t – 1) means the value in the previous year financial statemen

### See the table attached in the EL1 ###

Answer the following questions using the above dataset.
1. How many cases of manipulators versus non-manipulators are there in the dataset? Draw a bar plot to depict.
2. Create a 80:20 partition, and find how many positives are present in the test data.
3. The number of cases of manipulators are very less compared to non-manipulators. Use upsampling technique to create a balance dataset.
4. Build the following models using balanced dataset. Comment on which metric should be given preference for this dataset. Finalize the model for each technique after Hyperparameter tuning using GridsearchCV based on the metric selected. Compare the model performances with respect to different evaluation metrices.
a. Naïve Bayes
b. KNN
c. SVM
d. Logistic regression
e. Random Forest
f. Adaboost
g. Gradientboost
h. XGBoost
5. Comment on which are the most important features for predicting the manipulators.
6. The number of cases of manipulators are very less compared to non-manipulators. Use downsampling technique to create a balance dataset.
7. Compare the results of using both upsampling and downsampling techniques. Report the best model of all the models.
What
