# Basic-NLP-
BASIC NLP PIPELINE FOR A RESTAURANT REVIEW DATASET

The Multinomial Navie Bayes Algorithm (1-2 grams) performed the best out of the models, It is was expected as the bigrams capture phrases like very good, not good, highly recomment which a unigram model alone cannot capture.
The Word2Vec seems to be failing here, i cannot capture the natural phrases like "not good". Also we trained it on limited data so that might an issue.

Multinomial Navie Bayes Algorithm is fastest to train on sparse counts then logistic Regrssion and Linear SVM.

Inference is fast on Word2Vec in all of these models.
