# Portfolio
## #1: Kaggle MNIST Digit Recognizer
### A ResNet inspired approach
This notebook creates a submission to the [Kaggle](https://www.kaggle.com/) [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) competition. Kaggle provides a training set with 42,000 MNIST digit images and evaluates a submission on the 28,000 images in the test set. For my submission I train a residual neural network (ResNet) similar to the one provided in the book "Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow" by Aurélien Géron (p. 478). Using data augmentation and an Adam optimizer, this model achieves a 99.47% accuracy on the unseen test set.
