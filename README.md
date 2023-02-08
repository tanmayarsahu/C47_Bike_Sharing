
Project Name: Linear Regression Model on Bike sharing system 

Description:

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis 
for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is 
usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 
This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
 The company is finding it very difficult to sustain in the current market scenario. 
So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown 
comes to an end, and the economy restores to a healthy state.

Requirement:

The company wants to know:

    Which variables are significant in predicting the demand for shared bikes.
    How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, 
the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

Solution Algorithm:

The solution is divided into the following sections:

i) Data understanding and exploration
	1) load data from csv file
	2) Intial data Analysis
	3) Convert feature values to categorical values

ii) Data Visualisation
	4) Univariate analysis
    	5) Bi variate analysis
	6) Categorical Data Visualisation
	7) Drop columns that are not useful for analysis
	8) Numeric Data Visualisation
iii) Data preparation
	9) Creating dummy variables for categorical columns
	10) Splitting the Data into Training and Testing Sets
	11) Rescaling the Features

iv) Model building and evaluation
	12) Running RFE(recursive feature elimination) in Train data set
	13) Create model and Check P & VIF values (Irrarative Process)
	14) select a final Model based on Optimized P and VIF 
	15) Reduction analysis of training data
	16) Predictions and evaluation on the test set using Final Model
	17) Derive r^2 values and compare
	18) Publish the final Result


Programing:
We used Python Libraries such as pandas,numpy, matplotlib, seaborn, sklearn, statsmodels etc.

Final Result:
	We have published the final result of the Project 'Linear Regression Model on Bike sharing system'.
	Please check the file 'Bike_sharing.IPYNB'.