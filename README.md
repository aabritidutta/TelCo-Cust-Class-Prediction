# TelCo-Cust-Class-Prediction

Imagine a telecommunications provider has segmented its customer base by service usage patterns, categorizing the customers into four groups. 

If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. In this problem, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case.

The example focuses on using demographic data, such as region, age, and marital, to predict usage patterns.

The target field, called custcat, has four possible values that correspond to the four customer groups, as follows: 
1- Basic Service 
2- E-Service 
3- Plus Service 
4- Total Service

Performed a predictive analysis on the class of an unknown customer of telecom provider based on the service usage using k-NearestNeighbors.

## K-Nearest Neighbours

- K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.
- K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.
- K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.
- K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.
- K-NN is a non-parametric algorithm, which means it does not make any assumption on underlying data.
- It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it performs an action on the dataset.
- KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.

![image](https://user-images.githubusercontent.com/79006607/125520433-2f348063-2be2-4ee1-85e3-afef2a22348a.png)
