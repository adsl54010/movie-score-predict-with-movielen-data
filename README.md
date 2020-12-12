# movie-score-predict-with-movielen-data
movie-score-predict-with-movielen-data

colab link :https://colab.research.google.com/drive/11zOw-SQiexheL8qv4lgR4f39ps-nqo1f?usp=sharing

In this project, I am trying to predict movie score with data getting from grouplens.org and finally I got a 0.6 mse on 0.5 million testing data.

There are three sections.

First, I analysize data .

Second,there are tooo many data so I only keep data whose timestamp > 1530205000. After that, I still have 1.9 million data. 80% data for training and the others for testing.

Third, I use four different model to predict. They are Non-negative Matrix Factorization, Matrix Factorization base on Neural Network, Multilayer perceptron, NeuralCF.

In the end,Multilayer perceptron has the best result. 


Reference:

1.grouplens : https://grouplens.org/datasets/movielens/

2.tibame_recommender_system/NCF.ipynb : https://github.com/khuangaf/tibame_recommender_system/blob/master/NCF.ipynb

