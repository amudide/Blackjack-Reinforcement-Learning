# Blackjack-Reinforcement-Learning

The three fundamental machine learning paradigms are supervised learning, unsupervised learning and reinforcement learning. While supervised learning presents an agent with a data point and a correct label, reinforcement learning instead presents an agent with a data point, allows the agent to make a decision, and then later rewards/penalizes the agent based off of that and later decisions.

 

In my project, I train an agent to play the game of Blackjack using a model-free based approach called Q Learning. Q Learning learns the "quality" of a certain move given a current state, in terms of its expected discounted return. OpenAI, a recent development of Elon Musk, Sam Altman (and others), provides environments for games ranging from Pong to robotic hockey through their toolkit "Gym."  To train my agent, I first set up the environment using Gym, represented Blackjack as a Markov Decision Process (MDP), and then applied the standard Q Learning algorithm over hundreds of thousands of games. 

 

In the future, i'd like to expand upon this work by creating agents for more complex games using deep Q Learning (where the "quality" of a state-action pair is approximated by an artificial neural network rather than a look-up table).
