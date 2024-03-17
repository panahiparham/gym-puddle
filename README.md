# gym-puddle
Puddle world environment for OpenAI Gym with continuous state space and discrete action space.

<kbd>
  <img src='puddle_world.png'/>
</kbd>

## Installation
Run this line in the project directory.

`pip install -e .`

## Usage
```python
import gymnasium as gym
import gym_puddle # Don't forget this extra line!

env = gym.make('PuddleWorld-v0')
```

##  Notes
Rendering is available.

Run this line after each time step to see the puddles and agent location.
```python
env.render()
```

## References

Off-Policy Actor-Critic. Thomas Degris, Martha White, Richard S. Sutton. In *Proceedings of the Twenty-Ninth International Conference on Machine Learning (ICML)*, 2012.

http://rlpark.github.io/ (Java implementation)

https://github.com/samindaa/RLLib (C++ implementation)
