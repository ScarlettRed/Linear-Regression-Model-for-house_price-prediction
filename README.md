# Predicting House Prices: A Linear Regression Model
This repository contains a linear regression model with step-by-step explanation, implementation and prediction of house prices. There are a no. of files in this repository. Here is a guide of how to read them:
1. <b>home_data.sframe</b> - Dataset used.
2. <b>Analysis.ipnyb</b> - This file contains the initial analysis of the given dataset before model implementation.
3. <b>Single_feature_LRModel.ipynb</b> - Linear regression model w.r.t. a single feature.
4. <b> Multi-feature LR Model.ipnyb</b> - LInear regression model w.r.t. a no. of features.
5. <b> House price prediction.ipnyb</b> - Comparison and prediction of house prices for both models implemented earliear.
 
# What is Turicreate and SFrames?
Turicreate is a python library used to deal with big data. It is easy to use and can easily handle and manipulate data as compared to other python libraries. It is easy to use and you don't have to be an expert in Machine Learning to use this library. SFrames are used in turicreate to scale all the data used for model building. Turicreate is very much capable to build custom machine learning models in an easy go. 

# Installing Turicreate
It would be better if you create a virtual environment to run turicreate in jupyter notebook. Let's learn how to create virtual environment first.
### Creating virtual Environment
-> sudo apt-get install -y libstdc++6 python-setuptools <br/>
-> sudo apt-get install python3-pip <br/>
-> sudo pip3 install virtualenv <br/>
-> virtualenv venv <br/>
-> source venv/bin/activate  // This particular command will actiavte your virtual environment "venv".
### Now for installing turicreate:-
-> pip3 install turicreate

# Loading and Analysis of data
For this particular problem we are using dataset in form of Sframes. Here we are using "home_data.sframe" as our dataset. After the data is loaded we need to analyse the data first before implementing any model. turicreate.show() just shows all the statistical plots possible on the given dataset. Clear visualizations can be seen by implementing and improvising the code. From a particular scatter plot of 'price' vs 'sqft_living' we can see the factors for the implementation of a linear regression model here.

# Dataset splitting and linear regression implementation
We can specify the spliting proportion of dataset to train and test. After spliting the dataset we can implement the linear regression model. First we'll take only 1 feature to train and test the model. Then we'll try to retrain another model considering more than one feature. We can specify as much features as we want given in the dataset. We'll again train and test this model to predict house prices.

## CONCLUSION
During comparison we can see the difference in the house price predicted to the actual price given in the dataset; Model prediction much closer to the actual price is better than the other. In this way we can find out a better model for house price prediction based on the features included and excluded.
