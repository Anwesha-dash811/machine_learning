# machine_learning
CRITICAL REVIEW AND ANALYSIS OF LIBRARIES AND TECHNIQUES USED HERE
INTRODUCTION
Machine learning is usually of two types and those are supervised and unsupervised machine learning and these techniques are used to create the prediction models and analysis of the data.There is anothertype of machine learning technique which is semi-supervised learning but it is not used widely. In practical cases,supervised machie learning is used as all the data is labeled and the algorithms learn to predict the output from the input data only and it is quite simple to use and all datas are labeled which implies that implies that some data is already tagged with the correct answer such that the achine can predict the object easily as it is traied with the names previously but in unsupervised machine learning all the datas are unlabelled.Supervised learning problems can be grouped into regression and classification problems. The advantages of using supervised machine learning are that supervised machine learning allows collecting data and produce data output from the previous experiences.It helps to optimize performance criteria with the help of experience. It is the widely used machine learning in different practical fields. The various types of supervised machine learning algorithms and those are:
•	LINEAR REGRESSION:Regression technique predicts a single output value using training data.
•	LOGISTIC REGRESSION:Logistic regression method used to estimate discrete values based on given a set of independent variables. It helps you to predicts the probability of occurrence of an event by fitting data to a logit function.
•	Classification:Classification means to group the output inside a class. If the algorithm tries to label input into two distinct classes, it is called binary classification. Selecting between more than two classes is referred to as multiclass classification.
•	Naive Bayes Classifiers:Naive Bayesian model is easy to build and very useful for large datasets. This method is composed of direct acyclic graphs with one parent and several children. It assumes independence among child nodes separated from their parent.
•	Decision Trees:Decisions trees classify instance by sorting them based on the feature value. In this method, each mode is the feature of an instance. It should be classified, and every branch represents a value which the node can assume. It is a widely used technique for classification. In this method, classification is a tree which is known as a decision tree.
•	Support Vector Machine Here,it is required to create a predictive model which typically includes machine learning algorithm.The model is trained to respond to new data or values providing the results as per our requirement.There are two types of predidctive models and those are: Classification models and Regression models.The widely used predictive models are:
•	Decision Trees:Decision trees are a simple, but powerful form of multiple variable analysis. They are produced by algorithms that identify various ways of splitting data into branch-like segments. Decision trees partition data into subsets based on categories of input variables, helping you to understand someone’s path of decisions.
•	Neural Networks:Patterned after the operation of neuronsin the human brain, neural networks (also called artificial neural networks) are a variety of deep learning technologies. They’re typically used to solve complex pattern recognition problems – and are incredibly useful for analysing large data sets. They are great at handling nonlinear relationships in data – and work well when certain variables are unknown.
•	Regression(linear and logistic):Regression is one of the most popular methods in statistics. Regression analysis estimates relationships among variables, finding key patterns in large and diverse data sets and how they relate to each other.
Here we have used linear regression model to perform the predictive analysis.The equation of the linear regression line is in the form Y =mX+c, where X is the explanatory(independent) variable and Y is the dependent variable. The slope of the line is m, and c is the intercept (the value of y when x = 0).This procedure is used here for prediction analysis. Linear regression calculates an equation that minimizes the distance between the fitted line and all of the data points. Technically, ordinary least squares regression minimizes the sum of the squared residuals.A model fits the data well if the differences between the observed values and the model's predicted values are small.Residual plots can reveal unwanted residual patterns that indicate biased results more effectively than numbers. When your residual plots pass muster, you can trust your numerical results and check the goodness-of-fit statistics.
PROCEDURE
Pandas,numpy,seaborn,matplotlib and sklearn libraries are imported here as we have to read the dataset and explore the datas so,pandas is used here.Numpy is used for mathematical calculations to be performed here.Matplotlib and seaborn are used for visualization of plots.Sklearn is used for modelling.First the dataset is read using pandas and the columns,info and description of the dataset are explored which is called data exploration using the pandas. Then,visualizations are done comparing the month and the orders taken to find the amount of orders taken in a montha nd as per the last example given,the amount of orders predicted to be taken in the month of december and these visualizations are performed using matplotlib and seaborn.Line plot ans regression plot are performed using seaborn and others are ploted using matplotlib. Data training and testing is done in the second step to create the predictive model. The data is preapared first using pandas and then it is splited to train and test dataset.There are various methods to validate your model performance, I would suggest you to divide your train data set into Train and validate and build model based on 70% of train data set and then,it is finally trained and then those training and testing datas are plotted using the linear regression formula which is y=mx+c with the help of matplotlib library. These trained algorithms are used to predict the algorithms and find the predicted values.The predicted values and actual values are displayed and we can see that the actual and predicted values are same which means that the model is a good fit model but still we should calculate the accuracy of the model to find out if it is a good fit model or poor fit model or under fit model and finally we case to the conclusion that it is a good fit model The final step is to evaluate the performance of algorithm. This step is particularly important to compare how well different algorithms perform on a particular dataset. For simplicity here, we have chosen the mean square error.

CONCLUSION
Supervised Machine Learning algorithm was performed on the given data set to create a model for predicting the orders taken in various months and the model created here has got an accuracy of 100 %,which means it is a good fit model.

