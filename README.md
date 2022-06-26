# Project Name
> # A US-based housing company 
   


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

- What is the background of your project?
	-	The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- What is the business probem that your project is trying to solve?
    - We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
	- The company wants to know:
	    - Which variables are significant in predicting the price of a house, and
	    - How well those variables describe the price of a house.
	    - Also, determine the optimal value of lambda for ridge and lasso regression.
- What is the dataset that is being used?
	- For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
   - The optimal lambda value in case of Ridge and Lasso is as below:
        Ridge - 0.4
        Lasso - 0.0001

   - The Mean Squared error in case of Ridge and Lasso are:
        Ridge - 
                - MSE: 0.015888159710745184
                - RMSE : 0.1260482435845307
        Lasso - 
                - MSE : 0.01578521041943166
                - RMSE : 0.125639207333665


   - The Mean Squared Error of Lasso is slightly lower than that of Ridge . Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.

   - Hence the factors that generally affect an increase in the price  are :
               - Zoning classification,especially Low Density Residentials
               - Living area square feet,
               - Overall quality and condition of the house, 
               - Foundation type of the house, especially Poured Contrete	
               - Garage area that can  accomodated higher number of cars 
               - Total basement area in square feet and the 
               - Basement finished square feet area
               - 2nd Exterior 1st Exteriors like Vinyl Siding,Cement Board covering on house

   - ALso the factors that generally affect an decrease in the price  are :  
               - An increase in the Age of property
               - Physical Neighbourhood locations of Old Towns
               - 1st Exteriors like Vinyl Siding,Cement Board,Wood Siding covering on house
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Thanks to IITB and Upgrad team and coach for sharing the knowledge . 
- References 
	-  https://www.python.org


## Contact
Created by [@chandan11079] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->