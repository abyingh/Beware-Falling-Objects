In this project, we create an environment and an player with **Pygame**. The player a.k.a. AI agent, trains itself with *Deep Q-Learning*
algorithm in order to learn to **beware falling objects**. 

Everytime the AI agent collides with an object falling, it receives a penalty **(200P)**. Every second in the game yields a reward (1P) to the agent.
If the updated reward is less than zero, than the game starts again and learning process continues. 

The objective is to maximize the reward and stay as long as possible in the game.
