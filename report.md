# Algorithm
The code implements a Double Deep Q Learning algorithm with Prioritized Action Replay.

## Network Architecture
The neural network uses a Dueling Deep Q Learning architecture. It starts off with a layer of 150 neurons followed with a lyer of 50 neurons.
It then splits into two, using a layer of 50 neurons to estimate the advantages, and a similar layer to estimate the value. All layers use a relu activation,
except for the final advantage and value layers which use a linear activation.

# Hyperparameters
Learning Rate: 0.001, getting multiplied by 0.998 every episode
Update Frequency: Every 4 steps
Update Batch Size: 16
Epsilon: 0.3, minus 0.003 every episode
### Experience Action Replay

&alpha;: 0.9

&beta;: 0.6, plus 0.003 every episode until equal to 1

# Reward Plot
![graph](learning_curve.png)
