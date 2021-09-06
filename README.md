# Machine_Learning_Projects
HyperionDev Data Science (Level 3)
Level 3 Final Capstone project

* The purpose of this project is to try and classify a movie review as either positive or negative.
* The dataset used contain information about people reviews which indicate if they like or dislike the movie.
* To do this, we build a machine learning model to perform sentimental analysis using Recurrent Neural Network (RNN) in Keras  
  to classify the reviews as either positive/negative sentiment.
* In building an RNN model, we use the following architecture:

     # Embedding layer 
     # SpatialDroput1D(0.2)
     # BatchNormalization()
     # LSTM(32)
     # Dense(2, activation='softmax')

* The performance of the model showed an accuracy of about 59% and this was also verified in the prediction which made correct
  prediction of about 50% for the given data.
