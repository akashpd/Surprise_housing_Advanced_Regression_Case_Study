# Project Name
> In this project the aim is to build Advanced Regression Model using regularisation for Surprise Housing firm to understand how prices vary with predictors which will help the firm to predict the actual price and make decision to invest for high returns.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- As part of this Advanced regression assignment we have to submit two parts. 
Part-I is a programming assignment (Jupyter Notebook) 
Part-II includes subjective questions(in a PDF file)

- Background
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase 	houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data 	set from the sale of houses in Australia. The data is provided in the CSV file below.
	
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using 	regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

- The company wants to know:
	- Which variables are significant in predicting the price of a house, and
	- How well those variables describe the price of a house.

- Also, determine the optimal value of lambda for ridge and lasso regression.

- Business Goal 

- You are required to model the price of houses with the available independent variables. This model will then be used by the management to 	understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on 	areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new 	market.

- For this 'Train.csv' dataset is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Score for both Ridge and Lasso regression.
	- Ridge : Train :88.11 Test :88.20
	- Lasso : Train :87.64 Test :88.75
- Optimal value of lamda for both Ridge and Lasso regression.
	- Optimal Value of lamda for ridge : 10
	- Optimal Value of lamda for Lasso : 0.002

Top 5 most important varables/predictors are:
- AgeOfProperty
- SaleCondition_Partial
- SaleCondition_Normal
- SaleCondition_Family
- SaleCondition_Alloca

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.*
- Pandas
- NumPy
- SeaBorn
- MatPlotLib
- sklearn (Lasso,Ridge)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- I implemented this project as part of the Machine Learning - Linear Regression Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore (April -2022 batch).
- This project was based on [this tutorial](https://learn.upgrad.com/course/2880).


## Contact
Created by [@akashpd] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
