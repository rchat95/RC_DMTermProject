# Data Mining Term Project - Review Rating Predictor
Data Mining (CSE 5334) Term Project by Rongon Chatterjee
### Web Demo - http://rongonrc.pythonanywhere.com/
### YouTube Demo - 
### Contribution:
* In the reference, only one file from the data set is taken into consideration and multiple classifier models are applied to it. I used another file from the data set, "2020-08-19.csv" and tried to find patterns in it. For this, I removed the non numeric attributes and calculated the mean and standard deviation of each row in this file and used this to  develop clusters using the KMeans clustering algorithm.
* I also analyzed the correlation of the attributes with the average rating attribute to find any strongly correlated attributes, to see if regression could be used.
### Challenges:
* Performing operations and training a model on a data set containing 15823269 rows and 6 columns was a time consuming task.
* Improving model accuracy was difficult.
### Reference:
* https://www.kaggle.com/hakujouryu/starter-boardgamegeek-reviews-8f2079b5-d
* https://www.kaggle.com/pereirasteeven/board-game-rating-predictor
