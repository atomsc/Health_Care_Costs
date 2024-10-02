# Health_Care_Costs
EDA for various variables contributing to health costs.
[Jupyter Notebook Here](https://github.com/atomsc/Health_Care_Costs/blob/main/Health%20Care%20Charges.ipynb)

<a id='1'></a>
## Description
A spreadsheet of cleaned data for health care charges for a group of insured persons has been provided. The data scientist has been tasked with determining if a model can be created for predicting the charges a person will incur based on several variables of the person.

This data consists of 7 variables. This notebook will use the "Charges" as the target to predict. It will use the other 6 variables to attempt to predict the charges of the insured person.
- **Age:** Current age of the insured person.
- **Sex:** Sex of the insured person.
- **BMI:** The body mass index of the insured person. An indicator of possible health status based on height and weight
    - **Underweight:** < 18.5
    - **Normal:** 18.5-24.9
    - **Overweight:** 25.0-29.9
    - **Obese:** >= 30.0
- **Children:** Number of children the insured person has.
- **Smoker:** Current smoker status of the insured person.
- **Region:** Current region of the insured person.
- **Charges:** Health Care Billed Charges for the insured person.

<a id='2'></a>
## Objective
The objective is to use the given variables and attempt to create a model capable of predicting the health care charges that a person with a given set of attributes will incur. This data model will be useful in determining risk and determining the premiums that should be charged.

**Strategy**
1. Split the data to avoid snooping bias.
2. Explore the training set.
3. Visualize the data to find patterns.
4. Explore and build various models and select the best strategy.
5. Select a final model and save this model for future use.
6. As more data is collected, improve the model or build a different model.
