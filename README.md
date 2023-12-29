# Neural Network Workshop

This guide will lead you through the process of building a neural network using TensorFlow and Keras. You'll learn how to load data, construct a model, train it, and make predictions on the famous MNIST dataset.

## Objectives

For validation of this workshop you'll need to have a 95% accuracy submission on the digit recognizer competion.

 https://www.kaggle.com/competitions/digit-recognizer

Take a look at it.

Before diving into the practical steps, ensure tha you understand the basics what a neural network is and the problem you're solving.

## Step 1: Environment Setup

Install TensorFlow and Keras. (And Jupyter Notebook vscode extension if you are a good person)

* Install Jupyter Notebook extension on your vscode
* Install Pandas, TensorFlow and Keras.
* Make a .ipynb file (notebook file)
* Test the installation by importing TF and Keras in your notebook and running the cell.

## Step 2: Data Loading and Preprocessing

First go check up https://www.kaggle.com/competitions/digit-recognizer/data

* Download the train and test dataset
* Use pandas to load the train data from the just downloaded CSV file.
* Try to extract the label column from your data it's what you are trying to predict.
* Try to find out the shape of your data.

Bonus

* Split your data into training and validation sets.

## Step 3: Model Building

Construct a Sequential model with Keras with many cool layers. (Take a look at https://keras.io/api/)

* Initialize a Sequential model.
* Add layers (dense layers with relu should be a good start)
* Compile the model with an appropriate optimizer, loss function, and metrics.

Bonus

* Search about Convolutional layers, maxpooling and dropout

## Step 4: Training

Train the model using your training data.

* Train the model using `model.fit`.

Bonus

* Experiment with different batch sizes and epochs.
* Experiment with other layers, optimizers and

## Step 5: Predictions

Evaluate the model's performance and save it to disk.

* Load the test dataset (It should have no label column)
* Preprocess it as you did with the training data.
* Use the model to make predictions on the test data. (take a look at np.argmax)
* Save the prediction to a file (take a look at the expected format https://www.kaggle.com/competitions/digit-recognizer/data)

## Step 6: Submission

https://www.kaggle.com/competitions/digit-recognizer/submissions

* Go to the kaggle submission page and load the predictions file you produced
* If you have a red cross you made a mistake with the format
* Else you can go check your ranking and send your resume at openai.
