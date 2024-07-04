# svm_classifier
This project involves implementing a Support Vector Machine (SVM) from scratch in Python to classify the MNIST dataset digits into even and odd numbers. The SVM is trained using a linear kernel and optimized using gradient descent.

# Dataset Handling:

The MNIST dataset is loaded and preprocessed.
Digits are classified into two groups: even and odd, represented by +1 and -1 labels respectively.

# SVM Implementation:

# From Scratch: 
Implemented SVM with a linear kernel using gradient descent for optimization. This involved defining the SVM objective function, calculating gradients, and updating weights and biases iteratively.

# Scikit-learn: 
Utilized scikit-learn's SVM implementation with linear, polynomial, and Gaussian kernels for comparison.
Experimental Results:

# From Scratch SVM: 
Achieved an accuracy of 87.13% on the test set with the linear kernel. Observed potential overfitting with fewer training samples.

# Scikit-learn SVM: 
Compared various kernels (linear, polynomial, and Gaussian) and experimented with different hyperparameters. Achieved up to 98.73% accuracy with the polynomial kernel and observed challenges with the Gaussian kernel due to parameter tuning.

# Conclusion:
Found that SVMs with non-linear kernels (polynomial and Gaussian) outperform linear SVMs on this dataset.
Highlighted challenges with parameter tuning and computational complexity, especially with the Gaussian kernel.
