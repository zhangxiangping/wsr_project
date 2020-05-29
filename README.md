# wsr_project

# The source code for WSR.

### The pw_dataset can be obtained from https://github.com/zxp93/pw_data

Python Version: 3.5.6

library: 

nltk 3.3.0

numpy 1.14.2

gensim 3.4.0

sklearn 0.20.0

### You need to create a catelog for storing word2vec.model.

Usage(generating wsr):
1. mkdir model      //creating a catelog for storing word2vec.model by youself.

2. python word2vec.py       //obtaining word embedding for word in vocabulary.   (This isn't word2vec baseline method, just a step in the proposed method)

3. python wsr.py       //obtaining web service representation based on step 2. And evaluating the result of the proposed method.

This repo only contain wsr project code! The code of baseline methods can be found as following:
