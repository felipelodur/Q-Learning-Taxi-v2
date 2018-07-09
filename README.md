# Q-Learning-Taxi-v2

- **Goal:** Obtain a *Q-Learning table* with the optimal values for the Taxi-v2 problem.
- **Approach:** Since the goal is to obtain the optimal values for the Q-table, I have implemented an *exploration-only strategy*, namely *random exploration*. 
- **Correlated Problem:** If the goal was to learn the optimal policy as quick as possible there would be the need to implement a *exploration-exploitation strategy*, such as epsilon-greedy algorithm **[1]**.

### Taxi-v2: Open AI Gym
- **Open AI Gym:** [Gym](https://gym.openai.com/) is a toolkit for developing and comparing reinforcement learning algorithms.
Implementation of Q-Learning to learn optimal q-table of "Taxi-v2 Open AI Gym" and use it to solve the environment.
- **Taxi Environment:** [Taxi-v2](https://gym.openai.com/envs/Taxi-v2/) is a task introduced by Dietterich **[2]** to illustrate some issues in hierarchical reinforcement learning. There are 4 locations (labeled by different letters) and your job is to pick up the passenger at one location and drop him off in another. You receive +20 points for a successful dropoff, and lose 1 point for every timestep it takes. There is also a 10 point penalty for illegal pick-up and drop-off actions. The figure below illustrates the environment:

<p align="center">
<img src ="https://qph.fs.quoracdn.net/main-qimg-efa34695528d52dcd06c55d5d9b46bef-c" />
</p>

### References
**[1]** *Sutton, R. S. & Barto, A. G.* [Reinforcement learning: an introduction](http://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf), 1988.

**[2]** *T Erez, Y Tassa, E Todorov* [Hierarchical Reinforcement Learning with the MAXQ Value Function Decomposition](https://dl.acm.org/citation.cfm?id=1622268), 2011.
