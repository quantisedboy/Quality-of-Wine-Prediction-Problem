# Quality-of-Wine-Prediction-Problem

Predicting the Quality of a bottle of wine, based on some certain recorded features (using regression model)

Steps Taken :

1. Importing the necessary Python Libraries 
   a. Numpy
   b. pandas
   c. Scikit-learn
   d. Seaborne 
   e. statsmodels.api
   
2. Importing the wine data set from UCI Machine Learning Repository 
   Link : https://archive.ics.uci.edu/ml/datasets/Wine+Quality
   
3. Preprocessing the data set
    I.Dealing with missing values (The dreaded NaN)
   II.Feature Scaling .
   
4.Encoding Categorical Features with 1 : True and 0 : False 
    i.e for each category, creating a new column . Suppose our data set has categorical feature with 4 category, then I will create 
    4 new column for each of our category and remove the original feature column.
   
5. Selecting the most important features based on 
   I. Correlation between dependent and independent variable.
   II.Multicollinearity between independent features. (Using heatmap for visual understanding and also Variance Inflation Factor(VIF))
   
6. Checking for Outlier Point using Z-Score, and then depending on the value a course of action will be taken. 
   
7. Splitting the Data Set into 2 new Datasets : X and Y
   X: Independent Features 
   Y: Dependent Value 
   
8. Creating Training and Testing sets from both X and Y
    i.e xtrain, xtest and ytain, ytest.
    
9. Using Scikit-learn to import LinearRegression Model, and then using the Data sets labelled 'train' to train our model.
   I will also use Ordinary Least square method to create another model (so that i can tally their RMSE later).
   
10.Run the test data set on this models and check the output 

11.Analyze the model using 
  I.R^2 test
  II. RMSE value
  III. Using P-P plot to check whether the residuals are in Normal Distribution or not.
