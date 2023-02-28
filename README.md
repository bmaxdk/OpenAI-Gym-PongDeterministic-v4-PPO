# OpenAI-Gym-PongDeterministic-v4-PPO

[Pong-v0](https://gym.openai.com/envs/Pong-v0/#ale)
Maximize your score in the Atari 2600 game Pong. In this environment, the observation is an RGB image of the screen, which is an array of shape (210, 160, 3) Each action is repeatedly performed for a duration of kk frames, where kk is uniformly sampled from \{2, 3, 4\}{2,3,4}.

### Installation

```bash
$ pip install gym\[atari\]
$ pip install 'gym[atari]'
```

### Arguments
```
gym.make('PongDeterministic-v4')
```


### Instructions
* Follow the instructions in [`PongDeterministic-PPO.ipynb`](https://github.com/bmaxdk/OpenAI-Gym-PongDeterministic-v4-PPO/blob/main/PongDeterministic-PPO.ipynb) to train and run the agent!
```bash
$ git clone https://github.com/bmaxdk/OpenAI-Gym-PongDeterministic-v4-PPO
$ cd OpenAI-Gym-PongDeterministic-v4-PPO
```
