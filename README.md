# Quality-of-Wine-Prediction-Problem

Predicting the Quality of a bottle of wine, based on some certain recorded features (using multivariate regression model)  
library: Scikit Learn  
Dataset Source: [UCI ML Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/)  

Steps Taken :

 1. Importing the necessary Python Libraries   
   a. Numpy  
   b. pandas  
   c. Scikit-learn    
     
 2. Preprocessing the data set  
     Dealing with missing values (The dreaded NaN)    
      
 3.  Selecting the most important features based on   
     I. Correlation between dependent and independent variable.  
     II.Multicollinearity between independent features. (Using heatmap for visual understanding and also Variance Inflation Factor(VIF)).(NOT APPLIED)   
   
 7. Splitting the Data Set into 2 new Datasets : X and Y  
     X: Independent Features   
     Y: Dependent Value   
   
 8. Creating Training and Testing sets from both X and Y  
     i.e xtrain, xtest and ytain, ytest.  
    
 9.  Using Scikit-learn to import LinearRegression Model, and then using the Data sets labelled 'train' to train our model.  
     I will also use Ordinary Least square method to create another model (so that i can tally their RMSE later).  
   
10.  Run the test data set on this models and check the output   

11.  Analyze the model using   
     I.   R^2 test   
     
     Result "Red Wine": ( y_test : green line , y_Predicted : Red Line)   
     ![WInequality_red](https://user-images.githubusercontent.com/45620309/80868007-5dddaf00-8cb5-11ea-8830-412495cd94c1.png)
     
