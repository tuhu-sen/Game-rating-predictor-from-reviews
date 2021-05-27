# Game-rating-predictor-from-reviews

Contribution:

In the reference, only one file from the data set is taken into consideration and multiple classifier models are applied to it. I used another file from the data set, "2020-08-19.csv" and tried to find patterns in it. For this, I removed the non numeric attributes and calculated the mean and standard deviation of each row in this file and used this to develop clusters using the KMeans clustering algorithm.
I also analyzed the correlation of the attributes with the average rating attribute to find any strongly correlated attributes, to see if regression could be used.

Challenges:

Performing operations and training a model on a data set containing 15823269 rows and 6 columns was a time consuming task.
Improving model accuracy was difficult.

How to avoid overfitting?

On trying multiple classifier models, I observed that the ridge classifer performs decently well. The ridge classifier avoids overfitting by regularizing the weights to keep them small, and model selection is straight forward as we only have to choose the value of a single regression parameter

Reference:

https://www.kaggle.com/hakujouryu/starter-boardgamegeek-reviews-8f2079b5-d
https://www.kaggle.com/pereirasteeven/board-game-rating-predictor
