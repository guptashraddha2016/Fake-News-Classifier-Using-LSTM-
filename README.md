# Fake-News-Classifier-Using-LSTM
Perfrom fake news classifier using deep learning techniques.

# Files
1. Dataset
2. Fake new classifier using LSTM(jupyter notebook)
3. README File

# EXplaination
1) Pre-processing on dataset are used to clean the data.
   1. Firstly, all the sequences except english characters are removed from the title.
   2. Next, to avoid false predictions or ambiguity with upper and lowercase,all the characters in strings are converted to lowercase.
   3. Next, all the sentences are tokenized into words.
   4. To facilitate fast processing, stemming is applied to the tokenized words.
   5. Next, words are joined together and stored in the corpus.

2) Then a fake news detection model is built using LSTM

# Dataset
The dataset is taken from Kaggle. The data consists of 804 rows and 7 columns.
