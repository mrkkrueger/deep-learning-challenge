# deep-learning-challenge
Code for this project can be found in the main page in the file named "Starter_Code.ipynb". The code for this project came from in class examples, instructor deomonstration, and chat gpt.

## Overview of the Analysis
The purpose of this analysis was to help the nonprofit foundation Alphabet Soup select applicants to recieve funding who have the best chance of success.

## Results
* Data Preprocessing
- The target for this model was "IS_SUCCESSFUL". This variable stated if the applicants were successful or not in using the funds they received.
- Features for this model included income classification (INCOME_AMT), funding amount requested (ASK_AMT), and government organization classification (CLASSIFICATION)
- Variables that were removed because they were neither targets or features were the EIN and NAME variables. These were variables that were used for identification, but had no impact on on wether or not a project would be successful.

* Compiling, Training, and Evaluation the Model
- This model used four layers with ten neurons each
- I was not successfull in achieving the target model performance goal of 75%.
- Steps that I took in my attempts to reach the performance goal included adding more layers, removing layers, and creating more bins.

## Summary
*This model did a decent job of predicting success - was able to accurately predict it around 73% of the time. However, there is definetly room for improvement there. Given more time, and a less busy schedule, more combinations of neurons, layers, and variables could be tried 
