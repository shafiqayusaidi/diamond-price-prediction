# diamond-price-prediction

# SUMMARY

This project is to create a deep learning model using feed forward neural network by predicting the diamond price. The dataset is obtain from https://www.kaggle.com/datasets/shivam2503/diamonds

A correlation matrix map is plotted to evaluate which features contributes the most on the diagnosis of the tumour. From this matrix, it is concluded that the carat, clarity, depth and table features of the diamond contributes the most in this analysis.

<img width="831" alt="Screenshot 2022-04-29 at 00 32 45" src="https://user-images.githubusercontent.com/58509210/165801039-fda1429c-e135-44bc-97fc-101142f2738b.png">


The model is built with 1 input layer, 3 hidden layers, 1 dropout layer, and 1 output layer. 

<img width="421" alt="Screenshot 2022-04-29 at 00 41 23" src="https://user-images.githubusercontent.com/58509210/165802510-7b0efb0d-f3d4-41a6-a038-9b2b7f1ee1f3.png">


The model is trained using 50 epochs with a batch size of 100. An early stopping is added and the model stopped at epoch 14.

From the results obtained, the losses of the trained model are as follow:

Test Loss = 740198.625
Test MSE = 740198.625
Test MAE = 474.2000427246094

<img width="785" alt="Screenshot 2022-04-29 at 00 37 54" src="https://user-images.githubusercontent.com/58509210/165801969-01685867-324a-4ace-ae74-21e085510100.png">


A graph is plotted to display the predictions vs the actual diamond price. 

<img width="725" alt="Screenshot 2022-04-29 at 00 40 20" src="https://user-images.githubusercontent.com/58509210/165802302-cbc5602a-f602-4ec9-b8e5-711d38ad5eb5.png">



