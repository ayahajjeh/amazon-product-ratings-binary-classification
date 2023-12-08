# Binary Classification of Amazon Product Ratings
In this project, I used product reviews from Amazon to perform binary classification, where the goal is to identify if the review text represents a high-star review or a low-star review. For the purposes of this project, I define a high-star review as one with a score > 3 (i.e. a 4 or 5 star review), with low-star reviews being <= 3 (i.e. 1,2,3 star reviews).

For the first part, I built three binary classification models based on review text only. The three models were Logistic Regression, Support Vector Classifier, and Perceptron. I used functions in scikit-learn, numpy, and pandas.

For the second part, I use sentiment analysis only to predict amazon review scores. Sentiment analysis is the task of identifying if a text is generally positive, negative, or neutral. The task of binary amazon review classification is inherently related to the task of sentiment analysis. For example, it seems intuitive that a text with positive sentiment will have a high amazon review, right? For this part of the project, I explored the relationship between sentiment analysis and amazon review scores to try and identify how well sentiment scores can predict amazon review scores. In the attached write up, I report all the same metrics as in part 1 and include analysis as to why sentiment is or is not enough to perform amazon review predictions.

For the third part, I include the outputs of the sentiment model as a part of my best performing model from part 1 and re-run the binary classifier. By including both text features and sentiment features, I outperform my best model from part 1.

I evaluated all the models throughout this project using confusion matrix, ROC AUC score, accuracy score, and F1 score. Please look at the project write up, the pdf file uploaded in this repository, for a deep dive into this project description, processing, analysis, and results.
