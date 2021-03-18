# rl-policy-fusion

This project aims to fuse multiple Reinforcement Learning (RL) policies by performing layer-wise alignment of each policy network via Optimal Transport (OT). The matching neurons in each layer will then be fused using a variety of methods. 

## Dependencies
* Stable Baselines 3 is used to generate RL agents
* OpenAI Gym is used for environments
* Python Optimal Transport (POT) library is used for OT algorithms and solvers
