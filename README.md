# PREDICTION OF TERM DEPOSIT IN BANK AND TO IMPROVE THE EFFECTIVENESS OF THE BANK TELEMARKETING CAMPAIGN

## Project Overview
- Created a model that helps to identify the clients who will subscribe to the term deposit or not
- This model can save time and money to call mass clients randomly
- The data is related with direct marketing campaigns of a Portuguese banking institution.
- Data Cleaning, EDA , Feature Engieering Done before model buildig
- Logistic Regression,Descision Tree, RandomForest, KNearest Neighbour model was build to examine the best model
## Code and Resources Used

Python Version: 3.9.13
-Packages: pandas,numpy,seaborn,sklearn,matplotlib
-Sources: Created by: Paulo Cortez (Univ. Minho) and Sérgio Moro (ISCTE-IUL) @ 2012(https://data.world/uci/bank-marketing)

## Data Cleaning
-Null values and duplicate values are checked  and removed
-Missing values are cheacked
-Outliers are removed

##EDA
-I looked at the distribution of the data and the value counts for the various categorical variables. Below are a few highlights
![image](https://github.com/abhishk0403/Prediction_of_Term_Deposit/assets/140788396/51664c64-e0f3-487e-b1a7-11a5e5ae7f08)
![image](https://github.com/abhishk0403/Prediction_of_Term_Deposit/assets/140788396/9e342f68-7bff-4fd2-8c68-54b73e7f824e)
![image](https://github.com/abhishk0403/Prediction_of_Term_Deposit/assets/140788396/f0058b4a-dd40-4e5a-90d2-d674968fdc45)
![image](https://github.com/abhishk0403/Prediction_of_Term_Deposit/assets/140788396/5acbb20c-87fa-4fd8-a79d-de24210e8963)


## Model Building
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.
I tried four different models and evaluated them using accuracy score. I used accuracy score is a measure of how well the model correctly predicts the class labels of the instances in the dataset. The accuracy score is calculated as the ratio of correctly predicted instances to the total number of instances.Accuracy serves as a baseline metric that allows to compare the performance of your model against a simple baseline model that predicts the majority class for every instance.

I Applied Four Models here-
-Logistic Regression
Baseline for the model.Logistic Regression is specifically designed for binary classification problems, where the target variable has two classes So I chosed this model
-Decision trees 
It can be scalable to larger datasets, and their training time can be reasonable, especially with optimizations and parallelization techniques.So I chosed this model
-Random Forrest Classifier
Random Forests often provide high predictive accuracy, as they aggregate the predictions of multiple decision trees. The ensemble nature helps to reduce overfitting and variance, leading to robust and accurate models.
-KNN
 Sice KNN is a non-parametric algorithm, meaning it makes no assumptions about the underlying data distribution I thaght of giving it a try

 # Model Performance

 Random Forest Classifier far outperformed the other approaches on the test  
 -Logistic Regression: Accuracy Score = 81%    
 -Decision trees: Accuracy Score = 78%  
 -Random Forrest Classifier: Accuracy Score = 86%  
 - K Nearest Neighbour- 71%




