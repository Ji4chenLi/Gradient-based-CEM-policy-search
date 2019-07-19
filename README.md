# Gradient-based-CEM-policy-search

Gradient based CEM policy search

Current problem regards to the algorithm:

1. By executing the codes of CEM-RL, we finds that during the initial stage of training, CEM does not really contribute to the improvement of the policy. This observation can account for the current failure of our algorithm.

2. Actually, this algorithm algorithm has great potential. Not only for DDPG, the algorithm can adapt to any "Q-learning" style RL algorithm. With the support of the theory from GEM, our algorithm may increase the performance of model based RL, by treating the learned gradient as surrogate gradient.
