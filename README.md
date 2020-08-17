# Kaggle_Ludum_Dare_Prediction
Entry in the the [Kaggle Ludum Dare Prediction contest](https://www.kaggle.com/c/cs480-spring2020/overview)

My submission (teamname of "20655500_yang") officially clocked in at 6/123 (score of 0.93231 classification accuracy), 
but had I submitted my earlier attempt with a learning rate == 0.005 instead of 0.0045, I would have placed top 3/123 (score of 0.93404 classification accuracy)
with the exact same implementation otherwise.

My algorithm for the classification problem is centered around the use of [LightGBM](https://lightgbm.readthedocs.io/en/latest/Features.html), 
"a gradient boosting framework that uses tree based learning algorithms" developed by Microsoft Research.
