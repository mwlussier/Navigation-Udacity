
The first algorithm use is the vanilla Deep-Q Network.
We get to a maximum average score over 100 episodes of 15.0 in more or less 5 minutes (using CPU) with these hyperparameters:
  * Actions Selection: Epsilon-Greedy
  * Epsilon Decay: 0.90 
  * Gamma: 0.99
  * Learning Rate: 5e-4
  * Batch Size: 64 

The model architecture is three fully connected layers. The two first hidden layers are followed by a rectifier nonlinearity (max(0, x)).

Using the same hyperparameter except for the Epsilon Decay (which we dropped to 0.85), we've reached the maximum average score over 100 episodes of 15.0 in more or less 7 minutes (using CPU)

