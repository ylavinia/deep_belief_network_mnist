# deep_belief_network_mnist
Deep Belief Network using Theano evaluated on MNIST

This work implements Deep Belief Network (DBN) using Theano. The code generates the following:

1. Confusion matrix using Matplotlib

2. Filter image at an early epoch

3. Text file containing the error rates of each epoch

The modules ran on the following system configuration:

  Theano 0.7.0

  Python 3.3
  
  g++ 4.2
  
  NumPy 1.7.1
  
  SciPy 0.11
  
  Scikit-learn 0.16.1
  
  Pillow 3.0.0
  
  Matplotlib 1.4.3
  
  BLAS level 3

There are two dbn scripts: dbn_with_confusion_matrix.py and dbn_10percent_sample.py. The first uses the whole MNIST dataset while the second only uses 10 percent to make it quick for demo purposes.

The following are the modules needed to successfully run both dbn scripts:

logistic_sgd.py

mlp.py

rbm.py

utils.py

Run: python3 dbn_with_confusion_matrix.py

For demo, run: python3 dbn_10percent_sample.py
