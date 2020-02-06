# CTP_Wine_Quality
Notebook and lesson outline for CTP interview

Assumptions about student progress to this point:
Students come in to the lesson with an understanding of:
* Pandas dataframes and how to load data into a dataframe
* Exploratory data analysis in python
* Basic understanding of the machine learning process, specifically why we train test split and how to do it in sklearn

Lecture: 
The lab will be introduced with a lecture on some basic motivation for linear regression, including the idea that we're trying to find the line of best fit, how we generalize from a single feature to multiple features, maybe a brief description of ordinary least squares, and an overview of methods for evaluating our linear regression model. (Lecture plan to be fleshed out later)

Lab:
Students will be given the instructions below. Students will pair program in teams of two to follow the instructions as I circle the room and help troubleshoot. After about 15-20 minutes, or after most students have finished step 5, we'll come back together as a class and I will share my example code and we'll hear from students about alternate ways they solved the problem or difficulties they encountered. At this point 30 minutes will probably have passed, but I outlined my thoughts for the rest of the lab as well. The rest of the lab would consist of students experimenting with different ways to improve their base model, with some suggestions from me to get them started. We would come back together at the end to talk about what students tried and what was successful. 

Instructions for students:

* Step 1: Load the data into a dataframe.
* Step 2: Exploratory Data Analysis -- are there null values in the data? Are there any unexpected distributions? Do we need to do any data cleaning before feeding the data into a model?
* Step 3: Train-test split
* Step 4: Train a basic linear regression model. Using sklearn's LinearRegression from sklearn.linear_model, fit the model to the training data and then generate predictions on the test data.
* Step 5: Evaluate the base model using r-squared and root mean squared error metrics.
* Step 6: Iterate on the base model to see if we can improve our chosen metrics. Experiment with taking out different features. Use standard scaling to scale the features. 

Extension for students who finish the rest of the lab early: Try variations on linear regression such as ridge regression or lasso regression.

