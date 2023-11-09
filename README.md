# CodSoft-Tasks

The tasks that has to be completed to finish the internship CodSoft offered:
The Machine Learning tasks that we chose to complete are :
1. Movie Genre Classification

# Movie Genre Classification
In this task, the dataset provided to us contains the movie name with its genre containing summary of the movie. Based on its summary we have to classify what genre the movie belongs to. In order to proceed with this, we used Naive Bayes Classifier to predict the genre based on the words in the summary. Summary is ridden with unnessessary data like stopwords, punctuations and we need to remove them. Next we used TF-IDF to vectorize each word and assign support value to each word so that it is easy for Naive Bayes to classify the genre based on the support value of each word. This vectorized data is then used to train the data and finally predict the output.
