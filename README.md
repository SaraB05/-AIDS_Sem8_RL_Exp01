# Experiment 01 – Q-Learning Grid World

## Aim

To implement a simple grid-world environment and train an agent using the Q-learning algorithm.

## Problem Statement

Develop an environment where an agent learns to reach a goal state by selecting optimal actions using Q-learning.

## Brief Theory

Q-learning is an off-policy reinforcement learning algorithm that helps an agent learn the best action in a given state to maximize future rewards. It uses a Q-table that stores values for state-action pairs.

## Implementation Explanation

A grid-world environment is created and a Q-table is initialized. The agent explores the environment, receives rewards, and updates Q-values using the Q-learning update rule over multiple episodes.

## Results

The agent learns the optimal path to reach the goal after several training episodes.

## Conclusion

Q-learning successfully enables the agent to learn the best actions through interaction with the environment.

## References

1. https://www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/
2. https://www.analyticsvidhya.com/blog/2021/04/q-learning-algorithm-with-step-by-step-implementation-using-python/
