# Email_Spam_Detector
Email Spam Detector using Natural Language Processing and Deep Learning Classifiers.
In this project, two deep learning classifiers are compared for spam classification problem, Long-Short Term Memory (LSTM) and Convolutional Neural Network (CNN).
Also, non-sequential models are implemented to integrate Sentiment Ananlysis model using text Blob module, and features extracted from the Feature Engineering stage.

1. Preprocessing Datasets:
    - Lemmatization adn Stemming
    - Removing Stop Words
    - Tokenization
    - Embedding using Keras

2. Fine Tuning Hyper Paramters:
    - Loss Function
    - Optimizer
    - Embedding Depth
    - Number of Filters
    - Number of convolutional / LSTM layers

After comparing between all the impelemented models, LSTM with Sentiment Analysis non-sequential model achieved the highest accuracy of 97.4%
