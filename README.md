# Linear-Algebra---Credit-Card-Fraud-Detection
Downloaded the data from https://www.kaggle.com/dalpozz/creditcardfraud/data  Info about data: it is a CSV file, contains 31 features, the last feature is used to classify the transaction whether it is a fraud or not  Task 1: Done proper analysis of the whole data, plot all relevant plots, note down all observations.  Task 2: Let's define a matric similarity(i,j) = cosine^-1(dot product (vi, vj) / (length(vi) * length(vj)) ) Take out any sample from the data set which contains no less than 100 transactions, for every transaction in the sample find out top 10 transactions in the dataset which have the lowest similarity(i,j).  note: the sample should contain the similar distribution of classes as the original data set  ex:  Sample S = {1, 34, 989, 1000}  given transaction id = 1 , class = 1 ------------------- similar transactions ------------------- class = 1 # similarity = 0.0023 # transaction id = 0 class = 1 # similarity = 0.02312 # transaction id = 89 class = 1 # similarity = 0.02498 # transaction id = 2034 ... -------------------------------------------------------------------------- given transaction id = 34, class = 0 ------------------- similar transactions ------------------- class = 0 # similarity = 1.005 # transaction id = 523212 class = 1 # similarity = 1. 2673 # transaction id = 500001 class = 1 # similarity = 1. 3459 # transaction id = 24
Downloaded the data from https://www.kaggle.com/dalpozz/creditcardfraud/data

Info about data: it is a CSV file, contains 31 features, the last feature is used to classify the transaction whether it is a fraud or not

Task 1: Done proper analysis of the whole data, plot all relevant plots, note down all observations.

Task 2: Let's define a matric
similarity(i,j) = cosine^-1(dot product (vi, vj) / (length(vi) * length(vj)) )
Take out any sample from the data set which contains no less than 100 transactions, for every transaction in the sample find out top 10 transactions in the dataset which have the lowest similarity(i,j).

note: the sample should contain the similar distribution of classes as the original data set 
ex: 
Sample S = {1, 34, 989, 1000}

given transaction id = 1 , class = 1
-------------------
similar transactions
-------------------
class = 1 # similarity = 0.0023 # transaction id = 0
class = 1 # similarity = 0.02312 # transaction id = 89
class = 1 # similarity = 0.02498 # transaction id = 2034
...
--------------------------------------------------------------------------
given transaction id = 34, class = 0
-------------------
similar transactions
-------------------
class = 0 # similarity = 1.005 # transaction id = 523212
class = 1 # similarity = 1. 2673 # transaction id = 500001
class = 1 # similarity = 1. 3459 # transaction id = 24
