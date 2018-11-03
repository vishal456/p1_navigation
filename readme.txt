Details:
This repo contains solution for Banana Unity Environment.

Problem: Agent has to learn distinguish between yellow and blue banana. Aim of the agent is to pick up yellow banana and leave out blue banana.
We try to train a agent using deep reinforced learning to accomplish above task.

States:37 dimensions

Actions: 
	0 : move forward
	1 : move backward
	2 : turn left
	3 : turn right
Rewards:
	+1 : for collection yellow banana
	-1 : for collection blue banana

To solve this environment, we need to acheive a average score of 13 for 200 episodes.

For more details please check out this link: https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation

Dependencies File:
	requirements.txt
	use command : pip install -r requirements.txt

Main File: Navigation.ipynb
Running Trained Agent File: Navigation_Test.ipynb
Saved Weights File: checkpoint.pth
