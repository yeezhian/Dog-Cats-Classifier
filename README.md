# Dogs-Cats-Image-Classifier

## Dependencies
- Jupyter notebook

- Tensorflow 1.10
- Python 3.6
- Matplotlib
- Seaborn
- Scikit-Learn
- Pandas
- Numpy


In this case, I am working on classifier on image cats and dogs.

Step by Step Set up in Jupyter Notebook :
- directory for train and validate data.
- dimension of our image.
- parameters for NN model.
- Image data generator(Generates more images for better results/more generalized model)
- a basic CNN structure - feature detection layer(convolution2D , activation and pooling layer) then pass it to classification layer (Fully Connected , activation layer).
- Compile model
- Fit model 
- Plot accuracy and loss 
- Way of Improvement- adding regularization(dropout, recurrent dropout, L1, L2, pooling, early stopping)


# Future 
- We can add early stopping to the model so that it will stop when it detects if there is no improvement during the epochs. 
- trying different regularizer such as L1, recurrent dropout, weight and bias regularizer. 
- place more epochs and see whether the model will be overfitting. 
- You can always tune the batch size too. 
- Also plotting confusion matrix, AUC curve, learning curves(bias and variance) to have more ideas on how the model is working through time. 
- The more data, the better for the model, so that the model does not just memorized the pattern. (more generalized model)
- Deeper analysis - batch wise scaling, CIFAR(pixer scaling method) 
