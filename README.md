# Planar_data_classification_with_onehidden_layer
Planar Data Classification with One Hidden Layer (Version 6)

Overview

This project focuses on classifying data that resembles a flower, consisting of red and blue dots on a 2D plane. Logistic regression was initially used for classification, but it yielded a low accuracy of 47%. Since the flower data is not linearly separable, a neural network with one hidden layer was implemented for improved performance.
Neural Network Architecture

    Input Layer: 2 units
    Hidden Layer: 5 units
        Activation Function: Hyperbolic Tangent (tanh)
    Output Layer: 1 unit
        Activation Function: Sigmoid

Training Parameters

    Number of Iterations: 10,000
    Learning Rate: 1.02

Results

Various experiments were conducted with different numbers of hidden layers: 1, 2, 3, 4, 5, 20, and 50. It was observed that the best performance was achieved with 5 hidden units. Increasing the number of hidden units beyond 5 led to overfitting, resulting in poorer generalization.
Dependencies

    numpy: For numerical operations.
    scikit-learn (sklearn): For logistic regression.
    matplotlib: For data visualization.


How to Interpret the Results

    The code trains a neural network to classify the flower data into red and blue regions.
    The number of hidden units was experimentally determined as 5 for the best trade-off between bias and variance.
    Results may vary depending on the random initialization of weights and the data distribution.

Tips for Improvement

    Experiment with different hyperparameters, such as the learning rate, number of iterations, and the number of hidden units, to fine-tune the model's performance.
    Consider using a different activation function or regularization techniques to further improve the model's accuracy.

Acknowledgments

    This project was inspired by Andrew Ng's Deep Learning Specialization on Coursera.

License

This project is licensed under the MIT License - see the LICENSE file for details.
