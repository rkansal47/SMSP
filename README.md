# Sequential-Modeling-for-Soccer-Predictions

## Abstract

This project tested the effectiveness of using the sequential Hidden Markov Model (HMM) and Recurrent Neural Network (RNN) machine learning algorithms in predicting the results of soccer matches given a previous sequence of results for each team. This sequential approach in principle allows the models to consider temporal information about the team’s results, i.e. the team’s ‘form’, when predicting new results. This gives an opportunity to study how advantageous a sequential approach is as opposed to a non-sequential model for predicting soccer results, and how significant a team’s form is when predicting their future performances.

A neural network non-sequential baseline gave a prediction training accuracy of 37% and testing accuracy of 39%. The HMM got similar training and testing accuracies of 40% and 38% respectively. As opposed to this, the RNN was able to get training and testing accuracies of 65% and 54% respectively. This illustrates the RNN’s superiority over the HMM, that indeed a sequential model is a better predictor of match outcomes, and also that indeed a team’s form is significant in determining its future results.  

See Final Report.pdf for the full paper.
