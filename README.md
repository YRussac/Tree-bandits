# Tree-bandits


Online Learning Projet for ENSAE Project.
Based on the article "Bandit Algorithms for Tree Search" from Pierre-Arnaud Coquelin and Rémi Munos which is available [here](https://arxiv.org/abs/cs/0703062).

The idea was to compare different bandits algorithm on tree structure. 

In the notebook, the algorithms presented in the [article](https://arxiv.org/abs/cs/0703062) are implemented. We also present the results of the UCT algorithm on the comb tree. We remark that the transition phase of the exploration is really long (with the basic UCT model, after 1 million trajectories we didn't visit the optimal leave for the first time) as underlined in the paper.

Keywords: UCT, Flat_UCB, Modified UCT, BAST (bandits algorithm for tree search)
