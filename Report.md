
The first algorithm use is the vanilla Deep-Q Network.
We get to a maximum average score over 100 episodes of 15.0 in around 4 minutes with these hyperparameters:
  * Actions Selection: Epsilon-Greedy
  * Epsilon Decay: 0.90 
  * Gamma: 0.99
  * Learning Rate: 5e-4
  * Batch Size: 64 


Using the same hyperparameter except Epsilon Decay (which we dropped to 0.85), we've reached the maximum average score over 100 episodes of 15.0 in 

