# Alphabet-Classification
One Shot Learning using Siamese Network

It is the implementation of One Shot Learning using Siamese Network using Keras. One Shot Learning doesn't require a huge amount of data to train and classify amoung different classes and for doing so we would consider the siamese network which rather learning to classify images directly to any of the output class, it learns a similarity function which takes two images as input and expresses how similar they are.

We will use the Omniglot dataset which is a collection of 1623 hand drawn characters from 50 different alphabets. For every character there are just 20 examples, each drawn by a different person. Each image is a gray scale image of resolution 105x105.
You can download the dataset closing the github repository (https://github.com/brendenlake/omniglot).

\b{Inference:}

Clearly the Siamese Model performes much better than the Random Model and the Nearest Neighbor Model. However there is some gap between the results on training set and validation set which indicate that model is over fitting

\b{Conclusion:}

We obtained an accuracy of 72.8% in a 20 way one-shot learning and we have trained it in the google colab GPU.
