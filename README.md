# CBOW_IMDB
**CBOW Training for IMDB Review Classification** In this project, we implement the classification of IMDB Reviews using a LSTM. We examine two methods:
  - Classification w/ Self Pre-trained CBOW Vectors
  - Classification w/ 6B Pre-trained GLOVE vectors

For the second one, we first train a CBOW, and then use its pre-trained vectors to initialize the word embedding layer of the LSTM. For the later, pre-trained 6B GLOVE vectors are loaded.

| <center>Method</center>  | <center>Accuracy</center> |
|:--------------------------:|:--------------------------:|
| <center> w/ Self Pre-trained CBOW</center> | <center>71.75</center> |
| <center> w/ 6B Pre-trained GLOVE</center> | <center>75.08</center> |
