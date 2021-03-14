# Sequential-Modeling-for-Soccer-Predictions

## 2018 Abstract for COGS 185

This project tested the effectiveness of using the sequential Hidden Markov Model (HMM) and Recurrent Neural Network (RNN) machine learning algorithms in predicting the results of soccer matches given a previous sequence of results for each team. This sequential approach in principle allows the models to consider temporal information about the team’s results, i.e. the team’s ‘form’, when predicting new results. This gives an opportunity to study how advantageous a sequential approach is as opposed to a non-sequential model for predicting soccer results, and how significant a team’s form is when predicting their future performances.

A neural network non-sequential baseline gave a prediction training accuracy of 37% and testing accuracy of 39%. The HMM got similar training and testing accuracies of 40% and 38% respectively. As opposed to this, the RNN was able to get training and testing accuracies of 65% and 54% respectively. This illustrates the RNN’s superiority over the HMM, that indeed a sequential model is a better predictor of match outcomes, and also that indeed a team’s form is significant in determining its future results.  

## 2019 Abstract for COGS 191

This project is an extension of my COGS 185 project from last year which tested the effectiveness of using sequential models (Hidden Markov Model and Recurrent Neural Networks) in predicting the results of soccer matches given a previous sequence of results for each team (this was approved by Prof. Tu in office hours). Building upon the results of the previous paper, which concluded that RNNs are indeed effective in predicting results with training and testing accuracies of 65% and 54% respectively compared to a non-sequential neural network baseline of 37% and 39%, this experiment sought to optimize the model by testing cell types, architectures and various hyperparameters. It has produced a significant improvement over the previous paper’s results, with training and testing accuracies of 97% and 71% using a 1 layer, 300 cell, LSTM network with an input sequence length of 3. This demonstrates clearly sequential models can have extremely high accuracy in predicting soccer results with minimal data. 


For more details, see the [2018](https://github.com/rkansal47/SMSP/blob/master/Final%20Report%202018.pdf) and [2019](https://github.com/rkansal47/SMSP/blob/master/Final%20Report%202019.pdf) final reports. 

Notebook with pre-processing and training is [here](https://github.com/rkansal47/SMSP/blob/master/RNN_Non_Ternary.ipynb).
