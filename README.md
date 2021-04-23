# Neural_Network_Charity_Analysis
![](Images/network.PNG)

## Analysis Overview
Alphabet Soup is a nonprofit philanthropic foundation dedicated to helping organizations that protect the environment, improve peoples well being, and unify the world. Alaphabet Soup has raised and donated over 10 billion dollars in the past 20 years. 

Our job is to analyze the impact of each donation and vet out potential recipients. This helps ensure that the foundations money is being used effectively. We are tasked with designing and training a deep learning neural network that will predict which organizations are worth donating to and which are hight risk. This model will evaluate all types of input data and produce a clear decision making result. 

We will be designing and training our model using the Python TensorFlow library and a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Analysis Results
- Data Preprocessing 
	- The binary 'IS_SUCCESSFUL' variable is our target variable and let's us know if the money was used effectively. 
	- The rest of our beneficial variables make up our model features.  
		- 'APPLICATION_TYPE': Alphabet Soup application type
		- 'AFFILIATION': Affiliated sector of industry
		- 'CLASSIFICATION': Government organization classification
		- 'USE_CASE': Use case for funding
		- 'ORGANIZATION': Organization type
		- 'STATUS': Active status
		- 'INCOME_AMT': Income classification
		- 'SPECIAL_CONSIDERATIONS': Special consideration for application
		- 'ASK_AMT': Funding amount requested
	- We drop 'EIN' and 'NAME' because they are non-beneficial unique identifier variables and provide no predictive value to our model.

## Analysis Summary
