# Machine-Learning-with-Big-Data
Machine Learning projects with Big Data on Spark

LR and RF with optimal parameters<br />
In this assignment, our goal is to optimize the Multilayer Perceptron Model (MLP model) for both the given dataset and the application on unseen datasets. After building the MLP model, we will compare the AIC scores across different models to evaluate their performance. In addition, we will consider the absolute value of KL-Divergence and AIC score when selecting the best parameter for our model. Since AIC estimates the relative amount of information lost by a given model, we will minimize the AIC for our final model while minimizing the absolute value of KL-Divergence.

Make the Smallest CNN Model<br />
In this assignment, we are going to find out the model with smallest number of parameters while keep the model accuracy above 95%. We want smaller parameters because it can help prevent overfitting and improve generalization. Overfitting occurs when a model becomes too complex and begins to fit noise in the training data instead of learning the underlying patterns. Smaller parameters can help simplify the model and reduce the risk of overfitting. We first run experiments on different parameters in the CNN layers. After we found out the smallest model, we tried different activation function in the convolution/dense layer and tried different pooling type in the pooling layers.

Word2Vec<br />
In this assignment, we generate word2vec model which can perform the following tasks:<br />
Task 1: Try to make the (king) - (man) + (woman) produce queen with as high of a similarity
score as possible<br />
Task 2: Try to find a pair of synonyms with extremely high similarity score.<br />
Task 3: Try to find two words that are antonyms.<br />
