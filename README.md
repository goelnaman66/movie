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
Recommendations are based on similar users(UserBased Collaborative Filtering),similar movies (itemBased colaborative filtering), 
(in deployment the item based model exceeds the available memory limit on the free tier of Heroku so this has not been included)
