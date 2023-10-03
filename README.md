# Wide-and-Deep-Ann


Display Image Dimensions and Output:
Show the dimensions of the images in the CIFAR-10 dataset and what the output labels represent (e.g., different types of objects).

Data Splitting:
Divide the dataset into two parts: 15% for testing and the rest for training and validation. Make sure to mention that this division isn't the default behavior when reading the data.

Loss Function for the Last Layer:
Specify the loss function you plan to use for the last layer of your neural network. This will be important for model training.

Change Output Format:
Modify the output format in a way that allows you to use Categorical Cross-Entropy as the loss function for the last layer.

Create a Neural Network:
Build a neural network with a maximum of five hidden layers and use it to make predictions on the CIFAR-10 dataset.

Hyperparameter Tuning:
Optimize the hyperparameters of the model you've created. Report the method you used, the optimized outputs, and the time it took for optimization. You can consider using Keras Tuner for this purpose.

Performance Metrics:
Calculate and report performance metrics like accuracy, F1-score, and ROC AUC for your model on the training, validation, and test datasets. Present these results in a table.

Wide and Deep Network:
Design and implement a wide and deep neural network for the CIFAR-10 dataset. Compare its performance with the deep network from the previous step.
