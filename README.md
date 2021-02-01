# Starbucks_capstone. 
## Summary:  
In this project, I aim to apply the data science and data engineering skills learned in the Udacity Data Science Nanoprogram (also Udacity Machine Learning Nanoprogram) to analyze the data collected in a study when different Starbucks offers were sent to customers. Starbucks sent individual offers to their rewards members to increase their purchases. In this study, through data processing and visualization, as well as machine learing models, I wish to answer the following two questions:  
(1) Which offer type is most popular in term of how successful the offers were viewed and completed?  
(2) Based on demographic features such as “age”, “income”, “membership_days”, and “gender”, can we predict whether a customer will view/complete all the offers we send to them?  

## Content:
- "Starbucks ETL.ipynb": the notebook for the first half of the project. Here I explored the data, processed them to handle the missing values and make the dataframes more convenient for future analysis and modeling, and visualized the data to answer question 1. Then the cleaned and merged data were saved (two individual SQL database for "BOGO offers" and "discount offers").
- "Starbucks_ML.ipynb": the notebook for the second half of the project. Here I loaded the SQL database for the two types of offers, and trained random forest classifier model to identify whether a customer is a good "target" for each offer type, based on their demographic features. 
- "Merged_bogo_df" and "Merged_discount_df": the two SQL databases created by "Starbucks ETL.ipynb" that contains the merged and cleaned data for BOGO offers and discount offers, respectively. 
- "visuals.py": this is the Python codes to plot the predictive features with their normalized weights in the model. This was from "Udacity Machine Learning Nanoprogram" that I took last year.

## Acknowledgement:
This project is a part of the Udacity Data Scientist Nanodegree Program. The data was provided by Starbucks.
