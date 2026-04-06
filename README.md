# Deep Learning Architectures

This project explores several deep learning architectures using TensorFlow/Keras.

## Part A: Multilayer Perceptron (MLP)
I built an MLP using the Fashion-MNIST dataset. The model included multiple dense hidden layers and was evaluated on the test set. I also plotted training and validation accuracy/loss over epochs.

## Part B: Convolutional Neural Network (CNN)
I built a CNN using Fashion-MNIST. The model included convolutional layers, pooling layers, and dense output layers. I reported test accuracy, created a confusion matrix, and displayed correctly and incorrectly classified images.

## Part C: Recurrent Neural Network (RNN/LSTM)
I built an LSTM model using the IMDB movie review dataset for sentiment classification. The model was trained and evaluated on review text sequences, and I plotted performance over time.

## Results Summary
- The MLP performed well on image classification but was less effective than the CNN.
- The CNN performed best on Fashion-MNIST because it captured spatial features in images.
- The LSTM performed well on sentiment classification because it handled sequential text data effectively.

## Key Takeaways
Different neural network architectures are better suited to different types of data:
- MLPs work well for simple classification tasks
- CNNs are strong for image-based problems
- RNNs/LSTMs are useful for sequential text data
