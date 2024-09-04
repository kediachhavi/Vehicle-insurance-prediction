# Cross-sell Vehicle Insurance Prediction
***

## Background Information :
An Insurance company that provide Health Insurance to its customers, usually they offer other insurance product to the customers through diffirent kind of marketing channel. In this case we will build a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
***

## Problem Statement and Business Goals:
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
***

## Methodology:

 1. Data copying and cleaning:
    * Import the training data
    * Recategorize data
    * check for null values and other informations
    * drop the duplicate values
 
 3. Exploratory Data Analysis:
    * Conduct all the necessary EDA using various graphs on the dataset
    * interpret the graphs
  
 4. Feature Engineering
    * check for outliers
    * correlation among the features
    * perform one hot encoding in case of categorical features
    * Feature selection
    * Data handelling
    * Applying Random over sampler since the data is imbalanced

 5. Model Building:
    * Splitting data into Training and Testing
    * Standardize the data using Standard scalar
    * Creating a base model of prediction
    * 3 different models ( Logistic Regression, KNN Classifier and Random Forest Clasifier)
   
 6. Model Validation:
    * Check the model diagonistics (accuracy, precision, confusion matrix) all the base model
    * Choose which model has the best accuracy score.

 7. Model testing on test data:
    * Import the test data
    * recategorize it according to the training data
    * predict it using above model

 8. Model output saving:
    * Save the predicted data with IDs
    * Save as excel file (Submission.csv)
***

## Conclusions:
   * From this dataset of health insurance customers, we found that 87.7% of customers not interested in taking the vehicle insurance.
   * Out the interested 12.3% of the customers, 61% are males and rest are females implying males are mpre interested in taking the vehicle insurance.
   * Almost 95% of customers have a vehicle age that's less than 2 years. From our analysis, customers who has between 1-2 years and more than 2 years of vehicle age are more interested with vehicle insurance
     advertisment, while customers who has less then one year of vehicle age, only 4% of them are actually interesred with vehicle insurance.
   * There are customers from different age groups and customers between age group between 30-60 years are most likely to buy insurance.
   * The customers with age group 18-30 years already have the insurance that's why they are least likely to opt for vehicle insurance.
   * All the customers have driving license, only 0.2% of the customers does have one.
   * Customers with driving license are more interested in getting vehicle insurance.
   * We found out that customer who already have vehicle insurance are almost have no interest in another vehicle insurance. Our analysis shows that 99.9% of customers that have a vehicle insurance is not
     interested in another vehicle insurance, while customer who doesn't have a vehicle insurance 22.5 % of them are interested with vehicle insurance.
   * Customers who never had vehicle damaged only 0.5 % of those customers are intersted with vehicle insurance, 87% of customers who never had any vehicle damaged already have a vehicle insurance.
***  
 
## Model Results:


 ![model](https://github.com/Shipra-09/Project-Health-Insurance/assets/142134509/fd0e9a1b-776f-44eb-9881-4a2588931684)

   * The table is the evaluation matrix on all the algorithms, we are going to focus more on accuracy here.
   * It clearly shows that KNN classification has the best accuracy score with **0.899** recall score.
   * Please take a look at the machine learning modeling notebook for this classification cause if you need more details on the machine learning process, Thank you.
***
## Test data
   * The model is tested for the teat data.
   * Responses have been predicted using KNN classifiaction model.
   * The recorded reponses along with the customer ID's has been saved in file name : Submission.csv
   * This test data is visualized using Tableau.
   * Tableau file : Vehicle_Insurance_Prediction.twbx
*** 

## Contribution

Still Learning,

So feel free, Anything You wanna contirubute.

***
       
