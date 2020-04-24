# Deepleanring using tensorflow

### Image Processing and Classification using CNN & Transfer Leanring 
* Dropout
* maxpooling
* Image Augmentation 
* Convolutions 

### Times series Forecasting using 
* Moving Average & Naive Appraoch
* Linear model using Neural nets, dense layers
* RNN stateless(Sequence-vector & sequence-sequence for imporved speed))
* Stateful RNN 
* RNNs with LSTM cells 
* CNNs (using conv1D) - will create a model using weave-net model


Some more details 
### Overview and purpose 
Udacity - Intro to TensorFlow for Deep Learning : Lession 9 : NLP (Tweaking the model)
Tweaking the model for detecting sentiments
* Vocab size (consider over size of corpus) (while tokenizing)
* Padding (before or after)
* More or less embedding 
* Input length ( where to truncate)
* Number of embedding dimensions
* Flattend to GlobalAveragePooling1D (using the latter)

> For data follow: [https://gist.github.com/Kumaava]
> For code: [https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l09c05_nlp_tweaking_the_model.ipynb#scrollTo=SZzXE-pT8K57]

#### Use the link below to see how my network sees the sentiment related to each word from amazon and yelp reviews, visualizing embeddings: using embedding vector and meta data
http://projector.tensorflow.org/?config=https://gist.githubusercontent.com/Kumaava/8cd9aabaf3d56ac09fa6d4ac6e39d6f7/raw/999bcdf1dadb1bbda43f49a41133bcc596303dad/nlp:embedding_link

