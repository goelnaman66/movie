# Movie Recommendation App

This is a movie recommendation app build using React for the front-end, express for the back-end, flask for handelling the recommendations and mongoDB for the database.
***
SurpriseLib is used in this project to generate recommendations using a Cosine similarity-based nearest neighbours method. Dummy users are built using the moviewlens 100K dataset for testing purposes. There are at least 20 movie ratings for each user.
***
Link for flask backend server: 
***
![image](https://user-images.githubusercontent.com/56230034/170880146-461fc98e-477d-4240-844a-cb3e029080b7.png)
***
# Features of the App
```In today's hectic society, recommendation systems are becoming increasingly vital. People are constantly on the lookout for products and services that are tailored to their specific needs. As a result, recommendation systems are critical since they assist them in making the best decisions without having to use their cognitive resources.```
<br/>
<br/>
Recommendations are based on similar users(UserBased Collaborative Filtering),similar movies (itemBased colaborative filtering), KNN Baseline( A basic collaborative filtering algorithm taking into account a baseline rating), and NMF (A collaborative filtering algorithm based on Non-negative Matrix Factorization)
<br/>
<br/>
#<b>(in deployment of the flask server the item based model and knn baseline exceeds the available memory limit on the free tier of Heroku so this has not been included)
</b>
***![image](https://user-images.githubusercontent.com/56230034/170880769-72d93c59-258f-4ebb-b4da-2774ddcda642.png)***
<br/>

## 1. User Based Collaborative Filtering
<br/>
User-Based Collaborative Filtering is a technique used to predict the items that a user might like on the basis of ratings given to that item by the other users who have similar taste with that of the target user.
<br/>
![image](https://user-images.githubusercontent.com/56230034/170880960-bad251f5-6e44-4b2f-a3e5-3f092ad1990e.png)

## 2. Item Based Collaborative Filtering
<br/>
The fundamental assumption for this method is that a user gives similar ratings to similar movies Here, we explore the relationship between the pair of items (the user who liked Y, also liked Z).
![image](https://user-images.githubusercontent.com/56230034/170881797-a8f1505c-699a-48df-8feb-5395bc2db603.png)


## 3. Knn Baseline Collaborative Filtering
<br/>
A basic collaborative filtering algorithm taking into account a baseline rating.
![image](https://user-images.githubusercontent.com/56230034/170882080-c371dee1-07f5-4572-9cf6-cab449dd4d75.png)

## 4. NMF Based Collaborative Filtering
<br/>
A collaborative filtering algorithm based on Non-negative Matrix Factorization.
![image](https://user-images.githubusercontent.com/56230034/170882117-026d33b9-2483-4312-b735-61d9fa7289c8.png)


## 5. Analysis of Different Recommendation Algorithms
<br/>
![image](https://user-images.githubusercontent.com/56230034/170881599-00f7a0d5-9b78-4187-a9b0-3725b1a6f6ca.png)


