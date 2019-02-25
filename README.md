# Detecting-Language-by-Person-s-name


In this tutorial, we’ll build a [Recurrent Neural Network (RNN)](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html) in PyTorch that will classify people’s names by their languages. We assume that the reader has a basic understanding of [PyTorch](https://heartbeat.fritz.ai/introduction-to-pytorch-for-deep-learning-5b437cea90ac) and [machine learning in Python](https://heartbeat.fritz.ai/some-essential-hacks-and-tricks-for-machine-learning-with-python-5478bc6593f2).

At the end of this tutorial, we’ll be able to predict the language of the names based on their spelling. The dataset of names used in this tutorial can be downloaded [here](https://drive.google.com/uc?id=1Aw8EKmAaAJWL1hT6ASGOxCpurT-0oJr1). This tutorial has been adapted from [PyTorch’s](https://pytorch.org/) official docs— check out more about the implementation from these docs.


## Steps to be followed:
1. [Data Pre-processing](https://heartbeat.fritz.ai/data-preprocessing-and-visualization-implications-for-your-machine-learning-model-8dfbaaa51423
)
2. Turning the Names into PyTorch Tensors
3. Building the RNN
4. Testing the RNN
5. Training the RNN
6. Plotting the Results
7. Evaluating the Results
8. Predicting on New Names
9. Conclusion

