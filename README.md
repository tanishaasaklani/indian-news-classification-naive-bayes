# Indian News Article Classification using Naive Bayes

This project focuses on classifying Indian news articles into categories such as
Business, Politics, Defence, Sports, Technology, Education, and Entertainment
using Natural Language Processing techniques.

The model uses TF-IDF vectorization along with Multinomial Naive Bayes
for text classification.

A key challenge in the dataset was that articles related to politics and defence
were originally labeled under business. To address this, rule-based relabeling
was applied to improve category granularity before training the model.

Model performance was evaluated using accuracy(91%) and a confusion matrix.

This project is part of the 30 Days 30 Machine Learning Projects challenge.
