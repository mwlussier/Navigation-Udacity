## Vanilla Deep-Q Network

The first implementation is the vanilla Deep-Q Network algorithm.
We get to a maximum average score over 100 episodes of 15.0 in less than 400 episodes with these hyperparameters:
  * Actions Selection: Epsilon-Greedy
  * Epsilon Decay: 0.90
  * Gamma: 0.99
  * Learning Rate: 5e-4
  * Batch Size: 64

The model architecture is three fully connected layers. The two first hidden layers are followed by a rectifier nonlinearity (max(0, x)).

![alt text](https://github.com/mwlussier/Navigation-Udacity/blob/master/images/dqn.PNG)

Using the same hyperparameter except for the Epsilon Decay (which we dropped to 0.70), we've reached the maximum average score over 100 episodes of 15.0 in less than 300 episodes.


## Double Deep-Q Network

The second implementation is the Double Deep-Q Network algorithm.
The difference with the vanilla Deep-Q Network is that we use two different set of weight in our algorithm. One is used to select the best possible action and the other is used to fairly evaluate the value of this policy. These weights can be switch during the process to be updated symmetrically.

We get to a maximum average score over 100 episodes of 15.0 in less than 400 episodes with these hyperparameters:
  * Actions Selection: Epsilon-Greedy
  * Epsilon Decay: 0.85 
  * Gamma: 0.99
  * Learning Rate: 5e-4
  * Batch Size: 64
  
The model architecture is three fully connected layers. The two first hidden layers are followed by a rectifier nonlinearity (max(0, x)).

![alt text](https://github.com/mwlussier/Navigation-Udacity/blob/master/images/ddqn.PNG)
