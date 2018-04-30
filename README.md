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
- Data File: advertising.csv

#### 3) [Decision Trees & Random Forest](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Trees_Random_Forest)

##### [LendingClub.com data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Trees_Random_Forest/Trees_Random_Forest_Lending_Club_Decision.ipynb)
- Worked on Lending club data to predict if a borrower pays the money back to investor or not, using decision tree and random forest classifier
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

#### 7) [Movie Recommender System](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Recommender_System)

##### [Movie Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Recommender_System/Recommender_System.ipynb)
- Worked on Movie rating data from various users to find highly correlated movies to each other (according to ratings provided by different users) 
- Data File: Movie_Id_Titles, u.data

#### 8) [Natural Language Processing](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/NLP)

##### [Yelp Data Set from Kaggle](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/NLP/NLP_Yelp_Data.ipynb)
- Worked on Yelp data set to predict stars provided by reviewer using length of the text
- Created a function to remove the punctuation from the review and used stopwords() to remove stop words such as 'i', 'me', 'my', 'myself' etc.
- Used CountVectorizer to convert reviews in vectors of different words
- Using TfidfTransformer created inverse document frequency
- After that created prediction model using Multinomial Naive Bayes 
- Data File: yelp.csv

##### [Ham vs Spam](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/NLP/NLP_Spam_Ham.ipynb)
- Same steps were used as Yelp project but data was used from ('smsspamcollection/SMSSpamCollection')

#### 9) [Tensor Flow: MNIST Data set](https://github.com/kkaushi4/Machine-Learning-Case-Studies/tree/master/Tensor_Flow)
##### [MNIST Data](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Tensor_Flow/Tensor_Flow_MNIST_Data.ipynb)
- Worked on MNIST Data set and predicted the numerical value from images using TensorFlow library in Python 
- Data Set: MNIST

#### 10) [Ridge & Lasso Regression](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Regression/Ridge%20And%20Lasso%20Regression.ipynb)

- Worked on Data set and chose best parameter for Ridge and Lasso Regression using cross validation
- Data Set: test.csv, train.csv

#### 11) [Sentiment Analysis On Amazon’s Product](https://github.com/kkaushi4/Machine-Learning-Case-Studies/blob/master/Amazon_Product_Sentiment_Analysis/Amazon_Product_Sentiment_Analysis.ipynb)

- The project is based on providing any user, using Amazon (any Ecommerce site), identifying and decision making within initial 10 seconds on whether to buy a product or not based on user reviews given on the website. 

- Mainly, using Natural Language Processing and Sentiment Analysis in identifying whether a review by a user is positive or not. Algorithm helps any user who goes to any product page, extract all the reviews given and perform sentiment analysis on all the reviews and give a numeric prediction like out of say 10000 reviews 3000 are positive, 1500 are neutral and 5500 are negative.

- This will help the user in identifying whether to go for that product within 5 to 10 seconds instead of spending multiple minutes reading description, ratings, reviews etc. 


### Prerequisites
- Python 3.0
- Jupyter Notebook
- Libraries: numpy, sklearn, pandas, seaborn, matplotlib, tensorflow

