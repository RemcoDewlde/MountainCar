# MountainCar

## prerequisites
- python >3.5

## installation
    pip install -R requirements.txt
    

## Q-Learning

![Q-learning-algorithm](https://wikimedia.org/api/rest_v1/media/math/render/svg/47fa1e5cf8cf75996a777c11c7b9445dc96d4637)



## Q-Learning & Double Q-Learning
![Q-learning-algorithm](https://wikimedia.org/api/rest_v1/media/math/render/svg/4941acabf5144d1b3e9c271606011abdc0df444d)
![Double-Q-learning](https://wikimedia.org/api/rest_v1/media/math/render/svg/3e37476013126ddd4afdba69ef7b03767f4c4b75)

DQN, and similar algorithms like AlphaGo and TRPO, fall under the category of reinforcement learning (RL), a subset of machine learning.
In reinforcement learning, an agent exists within an environment and looks to maximize some kind of reward.
It takes an action, which changes the environment and feeds it the reward associated with that change.
Then it takes a look at its new state and settles on its next action, repeating the process endlessly or until the environment terminates.
This decision-making loop is more formally known as a Markov decision process (MDP).