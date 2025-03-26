# Genre-Predictor
Using the crux of Deep Learning, implemented a genre predictor using a NN.

## Description 
For this project, the dataset used is GTZAN Genre Classification dataset which consists of 1,000 audio tracks, each 30 seconds long. It contains 10 genres, each represented by 100 tracks.

The 10 genres are as follows:
Blues
Classical
Country
Disco
Hip-hop
Jazz
Metal
Pop
Reggae
Rock

## Model
For the CNN model, the Adam optimizer was used for training the model. The epoch that was chosen for the training model is 600.

All of the hidden layers are using the RELU activation function and the output layer uses the softmax function. The loss is calculated using the sparse_categorical_crossentropy function.
Dropout is used to prevent overfitting.

The model accuracy can be increased by further increasing the epochs but after a certain period, we may achieve a threshold, so the value should be determined accordingly.

The accuracy we achieved for the test set is 92.39 percent which is very decent.
