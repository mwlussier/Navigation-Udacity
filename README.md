# Navigation-Udacity
The objectif of this project is to train an agent to navigate in a large square world while collecting specific objects.
The project environment is provided by Udacity and is similar to, but not identical to the Banana Collector environment on the [Unity ML-Agents GitHub](https://github.com/Unity-Technologies/ml-agents) page.

The environment is a large square world filled with yellow and blue bananas.
The goal of the agent is to collect as many yelllow bananas as possible. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.
The agent interact in the environment through four discrete actions:

0. move forward
1. move backward
2. turn left
3. turn right

In order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

------

Follow the instructions below to be able to run the code.

## Step 1: Clone the DRLND Repository
Follow the instructions in the [DRLND GitHub](https://github.com/udacity/deep-reinforcement-learning#dependencies) repository to set up the Python environment. These instructions can be found in **README.md** at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.

## Step 2: Download the Unity Environment
It is not needed to install Unity - you can download the environment provided by Udacity from one of the links below. You only need to select the environment that matches your operating system:

  * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then, place the file in the _p1_navigation/_ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

------

To train the agent, follow the steps in Navigation_training.ipynb

To see the agent navigate in the environment, follow the steps in Navigation_test.ipynb

