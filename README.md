# Pirate Intelligent Agent: Treasure Hunt

## Project Overview

This project involved developing a pirate intelligent agent that uses reinforcement learning to navigate a maze and find treasure. The goal was to train the agent to learn an effective path through repeated attempts rather than relying on a manually programmed route.

### Project Work

The starter code provided the maze environment, the `TreasureMaze.py` and `GameExperience.py` files, the neural network model, and supporting functions for running the game and checking whether the agent completed the maze. The Jupyter Notebook also included the structure for the training function.

My main contribution was implementing the `qtrain()` function in the notebook. This included selecting actions, balancing exploration and exploitation, storing and reusing past experiences, training the neural network, and updating the target network. I also worked through implementation and runtime issues to get the training process working. This project helped me understand how reinforcement learning and neural networks can be combined to solve a problem through repeated feedback.

## What Computer Scientists Do and Why It Matters

Computer scientists solve problems by designing, developing, testing, and improving computational solutions. Their work matters because software and intelligent systems are used in areas such as communication, healthcare, business, and security. Understanding how these systems work also helps identify their limitations and prevent them from causing unintended problems. This project demonstrated how computer science concepts can be used to develop an agent that learns from its environment instead of following only a fixed set of instructions. Similar approaches can be applied to more complex problems, although a successful result in one environment does not guarantee that a system will perform correctly in every situation.

## How I Approach Problems as a Computer Scientist

I approach problems by breaking them into smaller parts, understanding what each part is responsible for, and testing solutions rather than assuming they will work. When something fails, I examine the error, identify possible causes, and make changes based on what the evidence shows. During this project, I had to understand how the maze environment, neural network, experience replay, and training process worked together. Troubleshooting the implementation reinforced the importance of testing and understanding the underlying logic instead of focusing only on getting the code to run. I also learned that training an intelligent agent requires experimentation and adjustments before it can perform its task reliably.

## Ethical Responsibilities to Users and Organizations

Computer scientists have a responsibility to develop systems that are reliable, secure, transparent about their limitations, and appropriate for their intended use. They must consider how a system's decisions affect users and the organization deploying it. They should also protect sensitive information, test for potential failures, and avoid making claims about a system's capabilities that the evidence does not support. Intelligent agents introduce additional responsibilities because their behavior is influenced by their training and objectives. A system might achieve its assigned goal without necessarily behaving as its developers intended in every situation. Developers must therefore test systems carefully, establish appropriate limits, monitor their behavior, and keep human oversight where necessary. This project was a relatively controlled maze environment, but the same principles matter even more when AI systems are used in real-world settings.
