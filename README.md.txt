# Digit Recognizer (CNN)

A convolutional neural network built with TensorFlow/Keras to classify
handwritten digits from the MNIST-style Kaggle Digit Recognizer dataset.

## Model
Conv2D(32) > MaxPool > Conv2D(64) > MaxPool > Flatten > Dense(128) > Dropout(0.3) > Dense(10, softmax)

## Data
Download train.csv and test.csv from the Kaggle "Digit Recognizer" competition
and put them next to the notebook.

## Run
pip install tensorflow pandas numpy matplotlib scikit-learn
jupyter notebook
