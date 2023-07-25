# WideBot-Task3
Task 3 - Classification
Using the same data in task 2, build a machine learning based classifier and show its 
performance on the test-set. Show precision, recall, f-score, accuracy for each class and for 
the whole test data. Please describe briefly the meaning of each result and metric for this 
specific task. Also, please write some enhancements that you may think about to achieve 
better results
#Explain:
1)The TfidfVectorizer is a tool used for feature extraction in natural language processing tasks.
tfidf_vectorizer = TfidfVectorizer() creates an instance of the TF-IDF vectorizer.
2)X is the feature matrix, obtained by applying the TF-IDF vectorizer on the combined cleaned text data from the 'story_clean' and 'title_clean' columns of the DataFrame df.
y represents the target variable, which is extracted from the 'topic' column of df.
3)train_test_split is a function used to split the data into training and testing sets.
X_train and y_train represent the training data and corresponding target labels, respectively. They contain 80% of the data for training the model.
X_test and y_test represent the testing data and corresponding target labels, respectively. They contain 20% of the data, which will be used to evaluate the model's performance. The test_size=0.2 argument specifies that the test set will be 20% of the entire dataset.
