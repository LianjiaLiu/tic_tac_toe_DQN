# tic_tac_toe_DQN
This is an excercise for training a Deep Q Learning(DQN) on the tic-tac-toe task from Gymnasium. Four component policies are given to evaluate the algorithm. The helper functions and opponent policies are provided by [Reinforcement Learning 23/24](https://mcms.cs.uni-saarland.de/rl/) team of Saarland University. The implementation of DQN is based on the [tutorial of DQN on CartPole-v1 task](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html).

## Remark
Tic-tac-toe is a classic problem which can even be solved by non-RL methods. The default parameter setting would seem overkill for such a task which may be the reason why few tic-tac-toe algorithm uses DQN. However this is just an excise for implementing DQN.

## Environment
 `gymnasium>=0.28.1`,  `python>=3.10.*` and `pytorch`

## Acknowledgments
Copyright of the function for loading opponent policies, interactions with Gymnasium environment and the provided opponent policies is under Reinforcement 23/24 team of Saarland University. 
