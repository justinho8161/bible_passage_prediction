# Bible Passage Case Study
I was given a dataset on bible passages and I had to predict the authors of the new testament with old testament data.
Throughout this process, I had to remap the author's names based on a very similar mapping to this table:
https://overviewbible.com/authors-who-wrote-bible/

Next, we had to convert the number of texts into integers in order to run our models against this. Count Vectorizer was used to perform this preprocessing. The text was used as our X features, while our dependent variable was the author's names.

These were the scores using multinomial bayes and logistic regression:
Multinomial Bayes
Accuracy of Training 62%
Accuracy of model 52%

Logistic Regression
Accuracy of Training 85%
Accuracy of model 59%

Next, we wanted to explore which features had the biggest impact on the model, so the package ELI5 was used.

[Here are the results](notebooks/results.pdf)
