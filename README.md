# AB_Testing

BANDIT_REWARD=[1,2,3,4] NUMBER_OF_TRIALS: 20000
1. Create a Bandit Class
2. Create EpsilonGreedy() and ThompsonSampling() classes and methods (inherited
from Bandit()).
1. Epsilon-greedy:
1. decay epsilon by 1/t
2. design the experiment 2. Thompson Sampling
1. design with known precision 2. design the experiment
3. Report:
1. Visualize the learning process for each algorithm (plot1())
2. Visualize cumulative rewards from E-Greedy and Thompson Sampling. 3. Store the rewards in a CSV file ({Bandit, Reward, Algorithm})
4. Print cumulative reward (try using the modified logging package)
5. Print cumulative regret (try using the modified logging package)
Note that the values of epsilon and precision are up to you to decide.
