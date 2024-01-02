# Health_Care_Costs
 EDA for various variables contributing to health costs. 

<a id = '1'> </a><h2>Description</h2>
<p>
A spreadsheet of cleaned data for health care charges for a group of insured persons has been provided. The data scientist has been tasked with determining if a model can be created for predicting the charges a person will incur based on several variables of the person.</p>
<p>This data consists of 7 variables. This notebook will use the "Charges" as the target to predict. It will use the other 6 variables to attempt to predict the charges of the insured person. 
</p>
<ul>
    <li><b>Age:</b> Current age of the insured person. </li>
    <li><b>Sex:</b> Sex of the insured person. </li>
    <li><b>BMI:</b> The body mass index of the insured person. An indicator of possible health status based on height and weight </li>
        <ul>
            <li><b>Underweight</b> < 18.5</li>
            <li><b>Normal</b> 18.5-24.9</li>
            <li><b>Overweight</b> 25.0-29.9</li>
            <li><b>Obese</b> >= 30.0</li> 
        </ul>
    <li><b>Children:</b> Number of children the insured person has. </li>
    <li><b>Smoker:</b> Current smoker status of the insured person. </li>
    <li><b>Region:</b> Current region of the insured person. </li>
    <li><b>Charges:</b> Health Care Billed Charges for the insured person. </li>
</ul>

<a id = '2'> </a><h2>Objective</h2>
<p>The objective is to use the given variables and attempt to create model capable of predicting the health care charges that person with a given set of attributes will incur. This data model will be useful in determining risk and determine the premiums that should be charged. </p>

<b>Strategy</b>
<ol>
    <li>Split the data to avoid snooping bias.</li>
    <li>Explore the training set.</li>
    <li>Visualize the data to find patterns.</li>
    <li>Explore and build various models and select the best strategy. </li>
    <li>Select a final model and save this model for future use. </li>
    <li>As more data is collected improve the model or build a different model.</li>
</ol>
