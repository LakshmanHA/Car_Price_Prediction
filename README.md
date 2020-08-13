# Car_Buyers_Classification
car buyers classification based upon their company past details.
This is the hackathon problem conducted by edurekha
# Plan
This is a 7 steps process.we need to come from scratch like,from Feature Enguneering to Model Prediction.
# Dependencies
we don't need any extra dependencies ,Google Colab is enough for this problem.
# step-1 & 2 Importing
First We need to import all the required modules and data required for our problem
# Step-3 Data preprocessing
-> converted total data into numeric values  
-> eliminated some columns which doesn’t show any impact on the dependent variable eg:car_company, model_id.  
-> encoded some categorical variables eg:feature1,  feature2.  
-> and also performed one hot encoding on some columns eg:fuel, car_type.  
-> finally converts any negatives in our dataset to zero
# Step-4 EDA
-> we need to select best features for the predicting car_Price  
-> I used a extra tree classifier algorithm for finding top 10 features  
-> from these 10 features again finding best features through backward elimination  
-> in the two algorithms features may be changing when we are re-executing the program so we need to change column names according to previous output
# Step-5 & 6 Model Fitting and Model Evaluation
-> fitted our data to random forest regressor after feature selection  
-> evaluated our model with r2_score  
-> we get good r2_score (0.95288)
# Final Step 
-> In this step we need to make our predictions





