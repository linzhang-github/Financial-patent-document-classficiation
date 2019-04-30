# Financial-patent-document-classficiation
This project is to process 882 financial patent documents with natural language processing and classify them into 9 categories with 96% accuracy. There are three main steps in this project listed in the following. 

- First, data processing and feature engineering with NLP and text topics modeling skills set, such as Tf-IDF, postag and N-grams language model. From those 882 patent documents, there are 17538 features generated, including the length of each document before text cleaning, length of each docoment after text cleaning, number of punctuations, number of adj in the doc, number of noun in the doc, number of verb in the doc, all the unique 1-gram word frequency, top 20 2-gram word frequency, and top 10 3-gram word frequency. After feature selection part through random forest algorithm, 300 most important features are selected for the documents classification step. 

-Secondly, apply 7 traditional classficiation machine learning algorithms with parameters tuning in the documents classfication part, including randome forst, gradient boost, linear SVM, logistic regression, gaussian SVM, KNN, and naive bayes. Among them all, randome forst has the best accuracy with 88%.   

-Thirdly, Neural Network(ANN), RNN, and LSTM are applied in the classfication part. After tuning the models, ANN has the best accuracy with 96% followed by LSTM 89.4% and RNN 88.9%. 


