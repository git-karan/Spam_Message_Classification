# Spam_Message_Classification
To predict whether a message is Spam or not.
Input: Raw Message String
Output: Spam or Not-Spam
In this project, text pre-processing is done on the raw message string, wherein stopwords are removed, stemming( using snowball stemmer) is done and few other things.
Text column is converted into vectors using CountVectorizer()
MultinomialNB() is used as the model to train the data and RandomSearchCV is used to tune the hyper-parameter.

