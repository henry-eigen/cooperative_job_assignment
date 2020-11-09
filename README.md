# ant_colony_optimization

An approach to solving a variation of the job scheduling problem using a method loosly based on ant colony optimization.

## The problem

Given a number of agents, and a number of tasks, each agent must choose a task in the hopes of maximizing total production.

Each agent has a productivity factor for each task.

The total reward of each task is subject to a function (i.e. not just linear)

## Contraints

Each agent only knows
 1. What its immediate neighbors estimate total work on each task
 2. The total number of agents in the grid
 
## Results

Using the distributed intelligence and an incrmental update approach taken from reinforcemtne learning, the agents are able to come to a solution which rewards in a higher reward than the greedy solution

## Motivation

In a complex system like an economy, every actor only has a small, local understanding of what is happening. Somehow though, a well functioning and cooperative system can emerge from this distributed intelligence. This is the first iteration of an attempt to better understand emergent cooperative behavior in systems with limited information.
