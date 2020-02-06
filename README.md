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
Students will be given the following instructions. Students will pair program in teams of two to follow the instructions as I circle the room and help troubleshoot. After about 10-15 minutes, or after a majority of students have finished step 5, we'll come back together as a class and I will share my example code and we'll here from students about alternate ways they solved the problem or difficulties they encountered. At this point 30 minutes will probably have passed, but I finished the rest of the lesson plan. Students would then experiment with different ways to improve their base model. We would come back together at the end to talk about what students tried and what was successful. 

Students will follow these steps, with example code in the jupyter notebook:
* Step 1: Load the data into a dataframe.
* Step 2: Exploratory Data Analysis -- do we need to do any data cleaning before building our model?
* Step 3: Train-test split
* Step 4: Train a basic linear regression model.
* Step 5: Evaluate the base model using r-squared and root mean squared error.
* Step 6: Iterate on the base model to see if we can improve our chosen metrics. Experiment with taking out different features. Use standard scaling to scale the features. 

Extension for students who finish the rest of the lab early: Try variations on linear regression such as ridge regression or lasso regression.

