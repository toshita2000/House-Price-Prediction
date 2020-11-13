# House-Price-Prediction
House Price Prediction using Regression Methods - Linear Regressor with ensemble methods gradientbooster and Random Forest Regressor <br> 
GRADIENT BOOSTING: <br>
Gradient boosting is another boosting model. Remember, boosting model’s key is learning from the previous mistakes.
Gradient Boosting learns from the mistake — residual error directly, rather than update the weights of data points.
Let’s illustrate how Gradient Boost learns.<br>
Step 1: Train a decision tree
Step 2: Apply the decision tree just trained to predict
Step 3: Calculate the residual of this decision tree, Save residual errors as the new y
Step 4: Repeat Step 1 (until the number of trees we set to train is reached)
Step 5: Make the final prediction
The Gradient Boosting makes a new prediction by simply adding up the predictions (of all trees).
 <br>

A Random Forest is a gathering strategy fit for performing both relapse and characterization assignments with the utilization of various choice trees and a procedure called Bootstrap and Aggregation, normally known as bagging. The fundamental thought behind this is to combine numerous choice trees in deciding the last yield as opposed to depending on singular choice trees. 
Random Forest has various choice trees as base learning models. decision tree is the base classifier for random forest. <br>

THEORY <br>
The main libraries used in the code are: - <br>
1.	Pandas
2.	Numpy
3.	Sklearn 
4.	Matplotlib
5.	Seaborn 
Pandas and NumPy are majorly used for mathematical computations purposes. For importing the dataset, we use the pd as the data frame to import the csv. This df is then used ahead for calling all the functions for data analysis and visualisation. Matplotlib and seaborn are used for data visualisation. The main plots used are scatter plots, bar plots, linear graphs. <br>
Sklearn is a machine learning library used for building the models. The main models used here are the Linear Regression, Linear Regression with ensemble methods and the Random forest classifier. <br>


