
# ant_colony_optimization

An approach to solving a variation of the job scheduling problem using a method loosly based on ant colony optimization.

## The problem

Given a number of agents and a number of tasks, each agent must choose a task in the hopes of maximizing total reward for the system as a whole.

Each agent has a productivity factor for each task.

The reward of each task is subject to a function of the total production of that task (i.e. reward is subject to diminishing returns, maximum threshold, etc.)

## Constraints

Each agent only knows
 1. Its immediate neighbors estimates of total work on each task
 2. The total number of agents in the grid
 
## Results

Using the system of distributed intelligence and an incremental update approach taken from reinforcement learning, the agents are able to come to a solution which results in a higher reward than that of the greedy solution.

Even though the solution found is suboptimal, the algorithm used grows with linear time complexity as the number of agents grows, this is favorable to the algorithm yielding the optimal solution which has exponential time complexity.

## Motivation

In a complex system like an economy, every actor only has a small, local understanding of what is happening. Somehow though, a well functioning and cooperative system can emerge from this system of independently acting agents each of whom only have a partial understanding of what others are doing. This is the first iteration of a project attempting to better understand emergent cooperative behavior.
