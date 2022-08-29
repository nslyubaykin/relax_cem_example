# Example CEM implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_cem_example/blob/master/cem_tutorial.ipynb) of cross entropy method (CEM) with ReLAx.

CEM actor was trained on HalfCheetah-v2 Mujoco Gym environment for 50k env-steps. 

The graph of average return vs training step is shown below (`batch_size=5000`):

![cem_training](https://github.com/nslyubaykin/relax_cem_example/blob/master/cem_training.png)

The graph below shows actual rewards vs rewards fitted with environment model:

![cem_model_rews](https://github.com/nslyubaykin/relax_cem_example/blob/master/cem_model_rews.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187185858-6659dd68-bb6f-4da6-bce7-c6a1d9c0e06d.mp4
