# Neural_Network_Charity_Analysis

## Overview

The purpose of this challenge was for us to get a basic understanding of machine learning and get started building basic predictive software. We were able to create a Neural
Network Binary Classification capable of predicting whether applicants will be successful if funded by Alphabet Soup. In order to achieve this, a CSV file containing more than 
34,000 organizations that have previously received funding from Alphabet Soup over the years is analyzed to evaluate and train data which will then serve in making a decision 
regarding successful applicants.

## Results

### Data Preprocessing  

The variable considered to be the target for the model is "IS_SUCCESSFUL".

The features of the model Include:

- Affiliation
- Classification
- Use_Case
- Organization
- Income_AMT
- Special_Considerations
- Status
- Ask_AMT
- Application_Type

Unnecessary variables such as "EIN" and "NAME" were removed from the data, as they are neither targets nor features.

Pre optimization our model had 2 layers the first with 8 neruons and the second with 6 neurons. Post optimization those numbers were increased to 15 and 8 respectively. 

###Summary 

Despite the measures taken, the target model performance of 75% accuracy was not achieved and there was almost no difference in the accuracy between the pre-optimized and the post-optimized data.

This could be explained by a number of factors such as:

A wrong activation function may have been used
The number of neurons used for the first and second layer needed to be changed
The deletion of columns may have significantly altered the result (if important columns were removed)
Different activation functions would require further testing to determine which one would be the most suitable to increase the accuracy level of the model
However, the training loss appears to have increased from 1.02 to 1.3 meaning simply adding neurons could inhibit this process slightly.

As a recommendation, a proper number of neurons as well as the right activation function need to be elaborated and chosen accurately with regards to the data in order to have a greater accuracy result.
