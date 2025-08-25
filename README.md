# Project Two – Treasure Hunt Intelligent Agent (Deep Q-Learning)

This repository contains my Jupyter Notebook implementation of a reinforcement learning agent for the **Treasure Hunt Pirate Game**, developed as part of my CS370 course on Emerging Trends in Computer Science. The agent uses **Deep Q-Learning** to navigate a maze environment and autonomously learn strategies to reach the treasure while avoiding obstacles.

---

## Reflection

### 1. What code was provided, and what did I create?
The project provided a starter framework with environment definitions (the maze grid, reward structure, and state transitions). My main contribution was implementing the **intelligent agent** itself using **Deep Q-Learning**. This included designing the neural network to approximate Q-values, setting up the replay memory, defining the training loop, tuning exploration vs exploitation (epsilon-greedy policy), and evaluating the agent’s performance over multiple episodes.

### 2. How does this connect to the larger field of computer science?
This project demonstrated how **machine learning** and **neural networks** can be applied to real-world problems that require decision-making under uncertainty. Reinforcement learning is central not only to game AI, but also to autonomous vehicles, robotics, and adaptive systems. By solving a constrained maze environment, I practiced concepts that scale up to **robot navigation, traffic optimization, and resource allocation**, showing how computational models can learn without explicit programming.

### 3. What do computer scientists do, and why does it matter?
Computer scientists design systems that **process information, solve problems, and extend human capability**. In this context, my work reflects how algorithms can replace intuition with systematic, repeatable strategies. This matters because AI-driven solutions influence nearly every field—from medicine and energy systems to transportation and education—helping societies become more efficient, safe, and innovative.

### 4. How do I approach a problem as a computer scientist?
I approach problems by **breaking them into smaller components**, identifying inputs, outputs, and constraints, and then selecting the right models or algorithms to bridge the gap. For this project, I first studied how a human would solve the maze, then translated that into reinforcement learning concepts (states, actions, rewards). From there, I implemented incremental tests—starting with basic Q-learning before extending to a neural network approximation—ensuring correctness at each stage.

### 5. What are my ethical responsibilities?
As a computer scientist, my ethical responsibilities are to design systems that are **safe, fair, and transparent**. AI agents must not only be effective but also accountable. In real-world deployments, this means ensuring that models are trained responsibly, that data biases are minimized, and that end users are protected from harm. For organizations, it means maintaining integrity, building trust, and designing systems that align with social and legal expectations.

---

## Conclusion
This project helped me cement my understanding of reinforcement learning and its connection to broader computer science principles. It reinforced the importance of exploration vs exploitation, the role of memory in training stable models, and the broader ethical context of deploying intelligent systems. This reflection will also serve as a guide when revisiting the project in the future as part of my professional portfolio.
