# ModelBased_BayesianRL
Bayesian reinforcement learning maintains a hidden belief state over the uncertainty of system transition dynamics. It provides the opportunity for the agent to act optimally under the dilemma of exploration and exploitation.

Solving the Bayesian reinforcement learning problem to get the offline policy in the belief space is computationally intractable. The contributions of this project are the following:
1. Formulate the Bayesian reinforcement learning in continuous belief space and  provide the equivalent representation in discrete space.
2. Provide an online solution for the agent to balance exploration and exploitation while inferring transition parameters using Thompson Sampling approximation.
3. Treat the online planning as a trial and embed the Experience Replay mechanism to train an experienced intelligent agent.

The algorithm is implemented on the classic Chain problem and a simple practical firefighting problem. The regret analysis is conducted for both cases to show the performance of the algorithm.

