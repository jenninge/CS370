# CS370
Current/Emerging Trends

# Description

This project utilized Deep Q-Learning to solve a treasure hunting game. The goal was to train an AI agent to solve the maze with the shortest path and with a 100%-win rate. The code provided included two python classes which was to create the game environment, and to store the episodes which contains the states in between the start and end of the game. A Jupyter Notebook was also provided which included code to play the game. I created the code to train the agent to solve the maze and find the treasure. The agent used exploration/exploitation to choose an action, then based off that action it would update its state, reward, and game status. Each episode was stored in an experience replay object to be used for future learning. The program utilized a Epsilon-Greedy Algorithm with the concept of exploration/exploitation. Ideally the AI agent would be exploiting more than exploring to solve the maze quicker.

