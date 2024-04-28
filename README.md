# Sentiment-Analysis-using-word-embedding
Here i have done sentiment analysis for urdu corpus using word embeddings
You have to download embeddings to proceed
This task uses same dataset as deep learning sentiment analysis dataset link :https://github.com/MuhammadYaseenKhan/Urdu-Sentiment-Corpus/blob/master/urdu-. Perform the task of binary classification on the dataset.
Choose one classifier from deep learning models implemented in prev task based on best
results on F-measure for binary classification.
Use following embedding for vector representation and report the results. You need to train
the embeddings yourself on the given Urdu dataset.
1) WordToVec

https://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/
2) Glove
https://nlp.stanford.edu/projects/glove/

https://medium.com/analytics-vidhya/basics-of-using-pre-trained-glove-vectors-in-
python-d38905f356db

3) Fasttext

https://blogs.sap.com/2019/07/03/glove-and-fasttext-two-popular-word-vector-
models-in-nlp/

https://fasttext.cc/docs/en/english-vectors.html
4) Elmo (it creates embeddings for sentences, so use entire tweet as imput to get the
vector) https://github.com/HIT-SCIR/ELMoForManyLangs

Calculate accuracy, Precision, Recall and F-score for all classifiers and report the results in
tables. For example, if LSTM (use any fixed hyper-parameters that gave best results) had best
overall results among deep learning models in your assignment 1 then make the following table
of results.
