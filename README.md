# Aspect-based-sentiment-analysis-using-Spacy-and-Textblob

Aspect-based sentiment analysis (ABSA) is a text analysis technique that categorizes data by aspect and identifies the sentiment attributed to each one. Aspect-based sentiment analysis can be used to analyze customer feedback by associating specific sentiments with different aspects of a product or service. 
#
By aspects, we mean the attributes or components of a product or service e.g. 'the user experience of a new product', 'the response time for a query or complaint', 'quality of food', etc. For example, a customer may write a review that the 'quality of food was bad' but 'the ambience was good'. Current models will give this sentence a neutral score of 0 because of the polarity of both sentiments. Our model should be able to identify both aspects and the associated sentiment to improve the service and serve their customers better.
# 
Here, I used Spacy to find out the different POS tags in a sentence and thus isolate the adjectives used to describe different subjects. Using TextBlob, I found out the sentiment score along with subjectivity (personal opinion subject to change depending on individual). I have used a NaiveBayesClassifier in TextBlob on a few sentences to train a classifier which will further be used to make predictions.
