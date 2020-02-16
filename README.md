# Udacity_DeepLearning_CharacterLevelRNNExercise
This is my implementation of the Character-based RNN Udacity exercise. 
The model generates sentences character by character, using its previous picks as inputs for the next.

## Dataset
The model was trained using the english version of the book **Anna Karenina**, stored at the path *./data/anna.txt*

## Architecture
The model has the following architecture:
- An **LSTM** with 2 hidden layers of 256 nodes 
- A **Batch Normalization** layer to avoid overfitting
- A **Fully Connected** layer for the output

## Training
The model was trained for 10 epochs using a 0.5 dropout probability for the **LSTM** nodes.

## Try it yourself
You can try the model yourself by cloning this repo and running the **Character_Level_RNN_Exercise.ipynb** notebook.
To make it work make sure you have the following packages:
- Numpy
- Torch
