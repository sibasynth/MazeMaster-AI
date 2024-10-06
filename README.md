# MazeMaster-AI: Reinforcement Learning for Navigating a Maze

## Summary

This project focuses on building an AI agent that learns to navigate through a maze using reinforcement learning. The agent is rewarded based on its proximity to the goal, measured by the Manhattan distance, and penalized when it hits walls or revisits the same locations. The objective is to train the agent to find the optimal path to the goal. Building AI course project.

## **Background**

The project addresses the challenge of enabling an AI agent to learn how to find an optimal path through an unknown environment, similar to scenarios in robotics and autonomous systems. I chose this project to gain a deeper understanding of reinforcement learning and its application to real-world problems. It’s important for understanding how AI can be used to learn and adapt in dynamic environments.

## **Some of the key problems solved include:**

How the AI agent can make real-time decisions to avoid obstacles.

How Manhattan distance is used to reward the agent when it approaches the goal.

How reinforcement learning can minimize the number of steps to reach the goal.

## **How is it used?**
The agent navigates through a labyrinth represented as a 2D array, where each cell is either an open path or a wall. Users can observe the agent's movement through the labyrinth using color codes, where blue represents the agent's current position and red represents walls.

## **Steps to use the solution:**
The agent starts from a given starting position and moves through the labyrinth. It receives rewards based on its Manhattan distance to the goal. The closer it gets to the goal, the higher the reward. Penalties are given for hitting walls or revisiting the same location. Once the agent finds the goal, its path is optimized based on accumulated rewards and penalties. The user can observe the agent's progress in real-time in the terminal.

## **Visualization of the AI Agent in the Maze**
![image of the AI agent in the Maze](/MazeMasterAI.jpg)


## **Data sources and AI methods**
The data for this project is generated in the form of a predefined labyrinth. The agent's decisions are based on an epsilon-greedy strategy, where it either explores new paths or exploits known paths. The reinforcement learning technique used is Q-learning, where each move updates the agent's Q-table based on the reward, a discount factor, and the Manhattan distance to the goal.

## **Challenges**
The project does not address issues related to complex or dynamic labyrinths where the structure changes over time. Additionally, the agent can get stuck in local minima, repeatedly revisiting certain areas. Ethical considerations include the potential resource-intensive nature of reinforcement learning, and safety concerns when applying AI to physical systems like robots.

## **What’s next?**
Next steps for the project could include:

Implementing Deep Q-learning to handle larger and more complex labyrinths.

Introducing dynamic obstacles in the labyrinth to simulate a changing environment.

Optimizing the agent’s learning rate and reward system through parameter fine-tuning.

## **Acknowledgments**

The project was inspired by theories of reinforcement learning and Q-learning. Special thanks to the "Building AI" course for providing the inspiration for this project.
