# Detecting-Personal-Health-Mentions-using-LSTM-Bi-LSTM-Networks

## Introduction
With the rapid growth of social media, platforms like Twitter serve as major sources for sharing real-time information, including personal health experiences. Automatically classifying tweets as or not as personal health mentions (PHM) can greatly support public health surveillance, disease tracking, and research. In this project, I implemented and compared two deep learning architectures “LSTM” and “Bi-LSTM” for binary tweet classification. The analysis focuses on model performance, computational efficiency, and overfitting behavior, with a particular focus on practical aspects of model implementation and evaluation using Keras.

## Dataset
Training Data : phm_train.csv (9991 labeled tweets)
Test Data : phm_test.csv (3331 labeled tweets)

## Model Architectures
LSTM: A recurrent neural network aimed to deal with the vanishing gradient problem present in traditional RNNs.
Bi-LSTM: An extension of LSTM that processes input sequences in both forward and backward directions, potentially capturing more context.

## Interpretation
Both models generalize well to the test set, with Bi-LSTM achieving a slight advantage (+0.57% accuracy) and a slightly lower loss. This improvement is consistent with its higher validation accuracy during training.

## Conclusion 
For this task, the LSTM model offers a strong balance between accuracy and efficiency, and Bi-LSTM may be preferred if the highest possible accuracy is desired, and resources allow.
