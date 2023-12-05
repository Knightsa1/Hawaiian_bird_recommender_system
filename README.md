# Hawaiian_bird_recommender_system

This project was from my Machine Learning Class. We were given a data set where the rows were like the title says Hawaiian Birds and the columns were a survey of which birds individuals saw during the study. Before the data was given to the class each of the features had five individual data points that were originally non-zero and that were set to zero. The idea behind the class project was to find a KMeans or KNN model that would give better recommendations as to what those missing points were.



Packages were not allowed on this project, and we need to write everything from scratch. Specifically, we coded and worked with the Manhattan, Cosine, and Minkowski distances. We also needed to find an appropriate K value for the KNN. We started with finding the distance that gave us the best results, which was Cosine, and then we moved on to finding the best K value. Our best results were K=25.



Finally, we needed to cross-validate our model and see if we truly found the best K value. Our lack of experience and time in the project led us to a brute force method. That simplified cross-validation approach showed that using  Cosine distance our best K value was somewhere between 25 and 30. It was a good attempt at cross-validation with plenty of room for growth.



Overall, I am proud of how my coding skills grew with this project simply from trying to build a KNN recommender system from scratch in R. It forced me to think and really understand the different parts of the model and how they worked together.


All

