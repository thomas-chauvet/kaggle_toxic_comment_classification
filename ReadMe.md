**Warning: The dataset contains a lot of dirty words, insults, etc. Please, consider it before checking the notebooks.**

## Slides

These notebooks were created in order to make a presentation about NLP and Keras, to show "how easy" it could be to create some neural networks for NLP problems with Keras. You can find slides [here](https://thomas-chauvet.github.io/kaggle_toxic_comment_classification/presentation/easy-nlp-with-keras.html#1).

## Notebooks to dive into NLP

Notebooks to understand Natural Language Processing (NLP) with Python. We use data from a [Kaggle Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) to find toxic comments in the Wikipedia forum.

Notebooks are splitted into 5 parts:

- [1_exploration.ipynb](https://github.com/thomas-chauvet/kaggle_toxic_comment_classification/blob/master/notebooks/1_exploration.ipynb): understanding data with wordcloud, NMF and TSNE.
- [2_logistic_regression.ipynb](https://github.com/thomas-chauvet/kaggle_toxic_comment_classification/blob/master/notebooks/2_logistic_regression.ipynb): playing with logistic regression in NLP context.
- [3_logistic_regression_pipeline.ipynb](https://github.com/thomas-chauvet/kaggle_toxic_comment_classification/blob/master/notebooks/3_logistic_regression_pipeline.ipynb): playing with logistic regression, a step further. We add [scikit-learn pipeline](https://scikit-learn.org/stable/tutorial/statistical_inference/putting_together.html) to automate our logistic regression and try to find the best logistic regression (ever ?).
- [4_deep_learning_for_nlp_intro_with_keras.ipynb](https://github.com/thomas-chauvet/kaggle_toxic_comment_classification/blob/master/notebooks/4_deep_learning_for_nlp_intro_with_keras.ipynb): playing from simple neural network to stacked bi-directionnal LSTM in order to compare performance with this different neural network architecture.
- [5_deep_learning_for_nlp_submission.ipynb](https://github.com/thomas-chauvet/kaggle_toxic_comment_classification/blob/master/notebooks/5_deep_learning_for_nlp_submission.ipynb): final neural network. A bi-directionnal LSTM with pooling and regularization.

Have fun!

## Play with notebooks

Do not hesitate to clone this repository to play with the notebooks.

You can use the conda environment provided with the `environment.yml` file. Use command `conda env create -f environment.yml`.

To avoid heavy computation on NMF and TSNE, we include in `data/work` some pickle with pre-computed NMF and TSNE.
