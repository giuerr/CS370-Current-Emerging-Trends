# CS370-Current-Emerging-Trends
AI pathfinding agent using deep Q-learning, reinforcement learning, and neural networks.
# Pirate Intelligent Agent – Deep Q-Learning

## Project Overview

In this project, I developed an intelligent pirate agent that uses deep Q-learning to solve a pathfinding problem. The goal of the pirate was to navigate through a maze containing obstacles and successfully reach the treasure. I was provided with starter code that created the maze environment and handled many of the basic game functions. This included code for representing the maze, determining valid actions, tracking the pirate's location, assigning rewards, storing experiences, and checking whether the pirate successfully reached the treasure.

My primary responsibility was completing the Q-training algorithm used to train the intelligent agent. I implemented the training process that allowed the pirate to repeatedly interact with the maze, select actions, receive rewards, store experiences, and use those experiences to train a neural network. The algorithm used both exploration and exploitation when selecting actions. Early in training, the pirate explored the environment by trying different actions. As the model improved, it increasingly exploited what it had learned by selecting actions based on the Q-values predicted by the neural network. I also used experience replay and a target network to help stabilize the learning process. The completed model was then evaluated to determine whether the pirate could successfully reach the treasure from different valid starting positions.

## What Do Computer Scientists Do and Why Does It Matter?

Computer scientists use computational methods to analyze problems and develop solutions that can be implemented through software and intelligent systems. Their work involves much more than simply writing code. They must understand a problem, determine its requirements, design an appropriate solution, test that solution, and improve it when necessary. Computer science matters because these solutions can automate difficult tasks, process large amounts of information, improve decision-making, and solve problems that would otherwise be difficult or time-consuming.

This project demonstrated this process through artificial intelligence. Instead of manually programming the exact path that the pirate should follow, I developed an intelligent agent capable of learning from its experiences. Reinforcement learning allowed the pirate to improve its decisions based on rewards and previous interactions with the environment.

## How Do I Approach a Problem as a Computer Scientist?

I approach a problem by first understanding what the program is expected to accomplish and then breaking that larger problem into smaller pieces. For the pirate intelligent agent, the overall goal was reaching the treasure, but accomplishing that goal required several smaller tasks. The agent needed to understand its current state, determine which actions were available, select an action, observe the result, and learn from that experience.

Testing and debugging are also important parts of my approach. During this project, I had to examine errors, understand how different functions interacted, and determine whether the training process was actually producing the expected behavior. I learned that developing an AI system involves experimentation and evaluation rather than simply writing an algorithm once and assuming that it works.

## What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, I have a responsibility to create systems that are reliable, secure, fair, and designed with the needs of users in mind. Developers should understand that the decisions made while designing algorithms can affect how those systems behave and how people are affected by them. This means considering issues such as privacy, security, bias, transparency, and the possibility of unintended outcomes.

I also have a responsibility to the organization to develop maintainable and reliable software while accurately communicating what a system can and cannot do. Artificial intelligence should not be presented as perfect or completely independent of human oversight. Developers should test AI systems carefully, document their limitations, protect the information they process, and consider the consequences of incorrect decisions. This course has shown me that responsible computer science requires considering both the technical performance of a system and the impact that the technology can have on the people who use it.
