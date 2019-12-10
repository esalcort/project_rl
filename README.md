# project_rl
Try RL policies for duckietown

We ran the policies on google colab. Se how at ([Run_policies.ipynb](https://github.com/esalcort/project_rl/blob/master/Run_policies.ipynb)).

For DDPG and SAC: 
Follow Duckietown instructions to install all the necessary dependencies
To run SAC for training: change directory to gym-duckietown/learning
```
  python3 -m reinforcement.pytorch.train_reinforcement --model sac
```
To run DDPG for training: change directory to gym-duckietown/learning
```
  python3 -m reinforcement.pytorch.train_reinforcement --model ddpg
```

The SAC and DDPG models are saved at:
```
  gym-duckietown/learning/reinforcement/pytorch/models
```
To run SAC for testing: change directory to gym-duckietown/learning
```
	python3 -m reinforcement.pytorch.enjoy_reinforcement --model sac
```
To run DDPG for training: change directory to gym-duckietown/learning
```
  python3 -m reinforcement.pytorch.enjoy_reinforcement --model ddpg
```


