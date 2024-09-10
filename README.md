# Baum-Welch-algorithm
stochastic processes final project

Imports: 
numpy is used for array manipulations 
scipy.special.logsumexp is used for numerical stability in computing logarithms

Forward Algorithm: Computes the probability of the observed sequence up to each time step, given the model parameters.
Backward Algorithm: Computes the probability of the remaining part of the sequence given the current state.

Baum-Welch Algorithm:
E-step: Calculates the probability distributions (gamma and xi).
M-step: Updates the model parameters based on gamma and xi.

Initialization: Parameters are initialized and updated based on the observed sequence.
