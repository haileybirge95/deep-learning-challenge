# Deep Learning Model: Alphabet Soup Nonprofit Funding

## Overview
The purpose of this tool and the insights it provides is to predict which applicants are most likely to succeed in their ventures. The analysis is based on records of over 34,000 organizations that have received funding from Alphabet Soup in the past. The relationships between features in the dataset allow this model to make predictions with calculated accuracy. 

## Results
- Data Preprocessing
  - The target of this model is the feature that indicates whether the applicant was successful.
  - The features of this model include defining characteristics of each applicant, from financial information such as income amount and asking amount to categorical data such as affiliation and organization type.
  - Some variables were removed from this model because they were neither targets nor features, the EIN number and the name of the organization. 
- Compiling, Training, and Evaluating the Model
  - A combination of numbers of neurons and layers were evaluated for this model, ultimately it appears that neither adding neurons or additional hidden layers improved accuracy over the original model.
  - I was not able to acheive target model performance.
  - In my attempts to improve model performance, I added and reduced neurons and epochs and added a third hidden layer. None were effective.
 
  ## Summary
  Overall, the original model was not improved upon in terms of accuracy. It is possible that a different model altering the activation functions could increase accuracy by utilizing a different gradient, which would change how weights are analyzed. 
