# Data Science project on HarvardX and MITx Open Online Course dataset

[orginal dataset](http://news.mit.edu/2014/mit-and-harvard-release-de-identified-learning-data-open-online-courses)

### Treatment of data
 * Used regression and decision tree to fill in missing values
 * Turned continuous class variable Grade into binary variable 'Good'/'Bad' grade
 * Designed Feedforward Neural Network to model the data and make predictions on class label

### Results
 * 98% accuracy, 80% precision, 80% recall
 * The features that had most impact on grades are:
 	* Education level
 	* Gender
 	* Whether the course you are taking is CS50X
 	* If you are from the United States or not