# Insulting-Comments

The data we are working on consist of 6182 comments that are collected from different forums. The comments are pre-labeled with 1(insult) and 0(neutral). The data is seperated in two files. First we have the train set that has 2898 prelabeled comments. The rest of the comments are not labeled and they concern the test set.
Our goal is to use different classification methods in order to predict the best possible results for the test set.
Some of the methods used in the code are SVM, Naive Bayes and Random Forest for the classification. We used tfidf and bag of words as the two arrays that would help with the calssification. Finally, we combined the part-of-speech method with the tfidf array and we applied the result to some of the classification methods. 
