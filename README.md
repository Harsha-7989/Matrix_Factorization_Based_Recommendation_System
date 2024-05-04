# Matrix_Factorization_Based_Recommendation_System

## Objective

This project delves into the 
development and evaluation of a specialized 
recommender system tailored to the sports and 
outdoor equipment domain. 

## Dataset Infromation

The dataset contains reviews of users who have bought sports and outdoor equipment products from Amazon from the period 2000-2018.
We can access the data using the link: (https://nijianmo.github.io/amazon/index.html) 
Only the columns pertaining to user ID, product ID and product rating were retained for the study. 
The dataset consisted of 2,839,940 rows. To manage this extensive dataset, only a random selection of 0.01% of the data was used for constructing the recommender models. The resulting data had 28399 rows.

## Proposed Methedology

Various algorithms are compared to find the best one. Parameters are tuned for each model to find the parameter combination which gives the best score. The best model is used to build the final recommender model. 

## Methedology

In this project, information pertaining to ratings of sports and outdoor products was employed in the construction of a recommender system based on collaborative filtering. Various algorithms such as singular value decomposition, neural matrix factorization and k nearest neighbours were tested with different combinations of parameters (such as learning rate and regularization rate) to find the best parameter combination for each algorithm. The best parameters were used to construct recommender models for predicting user ratings on products in the test set.

![image](https://github.com/Harsha-7989/Matrix_Factorization_Based_Recommendation_System/assets/86124041/6cb00284-cd0c-465d-bfc4-a32214e2812c)

## Results

![image](https://github.com/Harsha-7989/Matrix_Factorization_Based_Recommendation_System/assets/86124041/67078bda-0c0f-4e13-b812-fa6ccede557c)


![image](https://github.com/Harsha-7989/Matrix_Factorization_Based_Recommendation_System/assets/86124041/86ba856f-d837-4d8e-a6a8-3a3da4423ebf)



## Conclusion

The Singular Value Decomposition model obtained the best RMSE, MSE and MAE scores when compared to other algorithms considered in the study. This model was thus used to build the final recommender system for the data.

