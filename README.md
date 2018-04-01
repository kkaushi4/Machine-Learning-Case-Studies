# Machine Learning Code Using Python

This project contains various Machine Learning algorithms implemented using python 3.0 compiled on jupyter notebook. 

## Overview

Each folder containg .ipynb file. Some of the dataset used were imported from library and some are uploaded in the folders as .csv file.

### Machine Learning Algorithms:

#### 1) [Linear Regression](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Regression)

Project description
##### [E Commerce Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Regression/Linear_Regression_E_Commerce.ipynb) 
- Worked on E Commerce data to predict Yearly amount spent by Customer on app or on website
- Decided which factor affects the amount of money spent by customer, few of the factors are:
Avg. Session Length, Time on App, Time on Website & Length of Membership
- Data File: Ecommerce Customers.csv

#####  [Housing Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Regression/Linear_Regression_Housing.ipynb)
- Worked on USA Housing data to predict price of house using various factors such as:
Avg. Area Income, Avg. Area House Age, Avg. Area Number of Rooms, Avg. Area Number of Bedrooms & Area Population 
- Data File: USA_Housing.csv

#### 2) [Logistic Regression](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Regression)

##### [Titanic Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Regression/Logistic_Regression_Titanic.ipynb)
- Worked on Titanic data frame to predict survival or non survival of people on titanic
- Used mean to fill missing values
- Created dummy variables for categorical variables
- Data File: titanic_train.csv, titanic_test.csv

##### [Advertising Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Regression/Logistic_Regression_Advertising.ipynb)
- Worked on Advertising data to predict whether customer clicked on advertisement on not based on data available about various features 
- Data File: test.csv, train.csv

#### 3) [Decision Trees & Random Forest](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Trees_Random_Forest)

##### [LendingClub.com data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Trees_Random_Forest/Trees_Random_Forest_Lending_Club_Decision.ipynb)
- Worked on Lending club data to predict if a borrower pays the money back to investor or not using decision tree and random forest classifier
- Data File: loan_data.csv

##### [Kyphosis Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Trees_Random_Forest/Trees_Random_Forest_Kyphosis_Decision.ipynb)
- Predicted whether a person has Kyphosis or not using decision tree and random forest classifier based on data provided 
- Data File: kyphosis.csv

#### 4) [K Means Clustering](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/K_Mean_Clustering)

##### [University Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/K_Mean_Clustering/K_Means_Clustering_University_Data.ipynb)
- Used K mean clustering to clusters universities as Private or Public based on various features provided
- Data File: College_Data.csv

##### [Blob Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/K_Mean_Clustering/K_Means_Clustering_Blob_Data.ipynb)
- Used K mean clustering to clusters Blobs into 4 clusters 

#### 5) [K nearest Neighbor Classifier](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/KNN_Classifier)

##### [Classified Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/KNN_Classifier/KNN_Classified_Data.ipynb)
- Worked on classified data set from kaggle to do K Nearest Neighbor Classification
- Used StandardScaler() to scale the data
- Data File: Classified

#### 6) [Support Vector Machine](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/SVM)

##### [Breast Cancer Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/SVM/SVM_Brest_Cancer_Data.ipynb)
- Worked on Breast cancer data to predict whether a cell is cancer cell or not using Support Vector Machine (SVM) and GridSearchCV to predict parameters for C and gamma best for our model

##### [Iris Flower Data Set](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/SVM/SVM_Iris_Data.ipynb)
- Worked on Iris data set to predict various species of flower using Support Vector Machine (SVM) and GridSearchCV to predict parameters for C and gamma best for our model

### Prerequisites
- Python 3.0
- Jupyter Notebook
- Libraries: numpy, sklearn, pandas, seaborn, matplotlib, tensorflow

