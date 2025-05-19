# CS370
Current/Emerging Trends

# Description

This project utilized Deep Q-Learning to solve a treasure hunting game. The goal was to train an AI agent to solve the maze with the shortest path and with a 100%-win rate. The code included two python classes which were used to create the game environment, and to store the episodes which contain the states in between the start and end of the game. A Jupyter Notebook was also provided which included code to play the game. I created the code to train the agent to solve the maze and find the treasure. The agent used exploration/exploitation within the Epsilon-Greedy Algorithm, to choose an action, then based off that action it would update its state, reward, and game status. Ideally the AI agent would be exploiting more than exploring to solve the maze quicker. Each episode was stored in an experience replay object to be used for future learning. 

# Getting Started

Python Libraries Used:   
1) NumPy: Used to work with array objects quickly.
   [Guide](https://numpy.org/install/)
   
2) Keras: Deep-Learning API that supports TensorFlow
   [Guide](https://keras.io/getting_started/)

3) Matplotlib: Used to create visualizations
   [Guide](https://matplotlib.org/stable/users/getting_started/)
   

