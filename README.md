# CormacAssessment


Although logistic regression seemed like a viable solution for this problem, however it is possible there is a non-linear relationship between procedure attributes and outcome, making logistic regression not the best choice. With that in mind, I debated between using a neural network, a random forest model, or some other ensemble method. I think a random forest is the right level of complexity for this problem as well as dealing with feature collinearity by feature subsetting. I used PCA dimensionality reduction and gridsearch CV to finetune the model parameters.  
