# Predicting House Prices: A Linear Regression Model
A basic linear regression model which can predict the house prices of a particular area w.r.t. the given dataset, using SFRAMES in Turicreate.
 
# What is Turicreate?
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
We can specify the spliting proportion of dataset to train and test. After splitting the dataset we can implement the linear regression model. First we'll take only 1 feature to train and test the model. 
