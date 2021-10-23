# Twitter user gender prediction
In this project, Dataset of twitter users has been taken from kaggle. By processing this data, we can see that only text and description data of user is useeful to predict their
gender. So, all the other data has been removed and handled null values in rows and columns differently to process remaining data. Then, removed stop words and punctuations, 
tokenized words and applied stemming and lemmatization to text and description data using NLTK packages to clean data. After that, vectorized this data to create features which 
can be used to train model. At last, trained model using logistic regression and got almost 74% accuracy on test dataset.
