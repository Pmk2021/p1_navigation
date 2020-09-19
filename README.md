# p1_navigation
project 1 for deep reinforcement learning course on Udacity

## Environment
Each state is represented by an array with a length of 37. Each array contains the agent's velocity, and the location of objects in view of the agent.

There are 4 actions:  
move forward  
move backwards  
turn left  
turn right

The goal of the agent is to collect yellow banannas, and to avoid blue banannas. The reward for collecting a yellow bananna is +1, and the reward for a blue bananna is -1.

The environment is considered solved, when the agent achieves an average reward of 13 over 100 episodes
## Getting Started
First, start off by cloning the DRLND Repository from this link: https://github.com/udacity/deep-reinforcement-learning#dependencies
Follow the instructions to install the environment and all the packages needed to run the environment

To start, you need to download the environment by clicking on the link.

Linux: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip

Mac OSX: https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip

Windows (32-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip

Windows (64-bit): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip

Then after downloading the repository, unzip the file into the folder, making sure the file name in the second cell of navigation.ipyb matches the download

All the necessary packages are located in the requirements.txt file of this repository

## Instructions
Open Navigation.ipyb

To train the code, set the variable num_episodes in cell 7 to how long you want the agent to train. It took ~800 episodes to reach a mean score of 13 over 100 episodes. Then run the whole notebook. Once its finished training, it should save its weights and graph the agent's learning curve.

If you only want to see the agent play, run the first 5 cells to import all the packages and start up the environment. Then run the last cell to view the agent playing.
