### Neural network for learning Hooke's law

Trained on artificial data based on Hooke's law (Stress = Young's modulus * Strain), the NN (multi-layer perceptron) tries to learn the underlying law.
Effectively, it is learning the equation of a line with slope given by Young's modulus used for generating the data.
Even though the underlying function is a simple linear function, the NN is unable to infer stress correctly for strains outside the training range. However, with the use of L1 regularization on the activations of the hidden layers, this can be resolved.