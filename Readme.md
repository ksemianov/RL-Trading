
## [OpenAI Gym](https://gym.openai.com/) Environment for Trading

### Environment for reinforcement-learning algorithmic trading models

The Trading Environment provides an environment for single-instrument trading
using historical bar data. The code is based on [gym-trading](https://github.com/hackthemarket/gym-trading)

A number of RL-algos is used:
* Deep Q Learning (DQN)
* Cross-Entropy Method (CEM)
* Dueling Network DQN (DNDQN)
* State-Action-Reward-State-Action (SARSA)

### Installation
Install [keras-rl](https://github.com/matthiasplappert/keras-rl), [OpenAI Gym](https://github.com/openai/gym), seaborn (`sudo pip install seaborn`)

Then open this repo's root directory and type `sudo pip install -e .`

### Use

See [this jupyter notebook](https://github.com/ksemianov/RL-Trading/blob/master/gym_trading/envs/TradingEnv%20with%20keras-rl.ipynb) for more.


