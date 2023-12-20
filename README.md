# Deep-Learning
Submitted by -

Vishak Koundinya N 

4NI20IS125

VII sem ISE 'B' sec

Topic - Early Stopping

# Early Stopping :-
Early stopping is a form of regularization used to avoid overfitting on the training dataset. Early stopping keeps track of the validation loss, if the loss stops decreasing for several epochs in a row the training stops. The EarlyStopping class in pytorchtool.py is used to create an object to keep track of the validation loss while training a PyTorch model. It will save a checkpoint of the model each time the validation loss decrease. We set the patience argument in the EarlyStopping class to how many epochs we want to wait after the last time the validation loss improved before breaking the training loop.

In Regularization by Early Stopping, we stop training the model when the performance on the validation set is getting worse- increasing loss decreasing accuracy, or poorer scores of the scoring metric. By plotting the error on the training dataset and the validation dataset together, both the errors decrease with a number of iterations until the point where the model starts to overfit. After this point, the training error still decreases but the validation error increases.
