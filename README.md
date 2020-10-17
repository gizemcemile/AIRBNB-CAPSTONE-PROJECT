# AIRBNB-CAPSTONE-PROJECT

I explained my codes in Turkish. However, I want to introduce my notebook in English, too. 

Data is from kaggle.com. (https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings). I tried to predict in which country a new user will make his or her first booking. The most challenging part is dealing with an imbalanced target variable. The majority classes and minority classes have 'nt the same precision, recall, or accuracy scores. Since the problem is classifying customers' destinations as accurately as possible, checking the classification report is essential for us to respond correctly to customers' requests.

Higher scores are better. 

The precision is intuitively the ability of the classifier not to label as positive a sample that is negative(https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html.). 

Precision is a ratio. Let say you predict some people will go to US.(positive). They went US(true positive). Some of them went somewhere else.(false positive) True positive devided by total positive that some of them are true and some of them are false in presicion formula.(TP/(TP+FP))

The recall is intuitively the ability of the classifier to find all the positive samples.(https://scikit-learn.org/stable/modules/generated/sklearn.metrics.recall_score.html?highlight=recall#sklearn.metrics.recall_score) 

The recall is also a ratio. Let say you predict some people will go to US.(positive). They went US(true positive). Some of them didn't go there(negative). Besides, you predict some people won't go to the US, but they went US(false negative). True positive divided by the people who went to the US at the end of the day in recall formula.(TP/(TP+FN))

  Accuracy alone cannot be trusted to select a well-performing model since an imbalanced class problem exists in our case. Let you only have high accuracy for majority classes, your overall accuracy increases, although you have low scores for minority classes. 
 
 At the end of the project, I decided that there are seasonal effects. For further steps, I may try time series methods for classification problems. Or I will model the first date of booking at first, then the destination. 

