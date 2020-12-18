# Image-Classification-with-CNN

Explore the implementation of CNN with a color image dataset. MNIST, CIFAR-10, CIFAR-100 or MNIST-like and CIFAR-like are excluded.

Problem 1:
-----------------------------------------------------------------------------------------------------
a) Download the original dataset (cut in advance if necessary). You need less than 5-6 classes with no less than 1000 images for each of the classes in the training set, not less than 300 images for each of the classes in the validaiton set, and no less than 60 images for each of the classes in the test set. These numbers are approximate and you should follow the distribution ratio given. Split the dataset into three subsets: training, validation and a test set following the ratio (70%-20%-10%). Use dataset analysis and preprocessing as normalization or standardication etc. Represent the classes in training and validation sets in the following two ways shown below for training set. Do the same for validation set. Make convolusions about the imbalance of the trianing and validation sets and pick up the way to fix the imbalance problem of both datasets: training and validation.

For testing set provide the same information without considering the issue of imbalance

b) Use Sequential model and build the topology of your CNN implementing unbalanced dataset as well the balanced training and validation datasets. Your CNN topology should include no less than four convolutional layers, where the number of neurons, the number of filters and their size and the type of pooling layers and where to include the last one is up to you. Do experiments with 3 different models (the difference could be in the choice of activation function, optimizer, and number of convolutional layers, batch size or any combination of these, learning rate change, stride etc.). Include as a first choice ReLU, Adam and batch size 32. Do not forget batch normalization and shuffling. Describe each model. Apply regularization and dropout to the model to prevent overfitting if necessary.

c) Plot training and validation accuracy as well as training and validation loss for each of the above models using combinations like the one shown below.

d) Display some channels in every intermediate activations and explain why this is useful.

e) Visualize (display) convolutional filters: get the gradient of the loss with regard to the input, apply stochastic gradient descent, include a code for filter visualizations and generate a grid of some filter response patterns in a layer.

Problem 2: 
-----------------------------------------------------------------------------------------------------
Perform testing. Get the predicted class – show some correctly and not correctly predicted
images of testing set as below. Evaluate test results using confusion matrix, classification report
(precision, recall, f1-score, support, ROC/AUC and Precision-Recall curves). Except tables for this
evaluation provide graphics of normalized confusion matrix as shown below, ROC/AUC curves as
the one below.

Implement any ENSEMBLING you want and present the results in a table as shown below as well
as confusion matrix of your ensemble:

-----------------------------------------------------------------------------------------------------
EDIT:
** Forgot ensambling and need to fix contfusion matrix **

-----------------------------------------------------------------------------------------------------
NNDL_Proj1_Problem1: added to repositroy to show how I initially manipulated the dataset
NNDL_Proj1_Problems1&2: official fully done project (forgot ensembling and confusion matrix is not colored)
