## Reinforcement Learning related paper

#### 1. Playing Atari with Deep Reinforcement Learning
1. Learning to control agents directly from high-dimensional sensory inputs like vision and speech is one of the long-standing challenges of reinforcement learning.
2. RL algorithms must be able to learn from a scalar reward signal that is frequently sparse, noisy and delayed. The delay between actions and resulting rewards, which can be thousands of timesteps long, seems particularly daunting when compared to the direct association between inputs and targets found in supervised learning.
3. This paper demonstrates that a convolutional neural network can overcome these challenges to learn successful control policies from raw video data in complex RL environments.
4. The goal of the agent is to interact with the emulator by selecting actions in a way that maximises future rewards.
5. The basic idea behind many reinforcement learning algorithms is to estimate the actionsvalue function.
6. Deep neural networks have been used to estimate the environment E; restricted Boltzmann machines have been used to estimate the value function or the policy.
7. The divergence issues with Q-learning have been partially addressed by gradient temporal-difference methods.