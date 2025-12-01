---
layout: post
title: "Reliable Offline Reinforcement Learning"
date: 2026-03-18
categories: jekyll update
---

Safety is a crucial concern when deploying reinforcement learning (RL) algorithms in real-world applications. Furthermore, safety has many dimensions, ranging from ensuring reasonable performance to respecting predefined constraints.

In this talk, we focus on safety from an offline perspective, where the RL agent only has access to a fixed dataset of prior trajectories, without direct interactions with the environment. Given the availability of the behavior policy responsible for data collection, the primary challenge is crafting a policy that outperforms such a behavior policy.

We will present algorithms that leverage the behavior policy to compute an improved policy with high probability and discuss how to exploit the environment's structure to improve sample efficiency.

# Speaker
[Thiago D. Simão](https://tdsimao.github.io/) is an [assistant professor at Eindhoven University of Technology](https://dai.win.tue.nl/).

# Time and Place
Monday 18/03/2026 at 13:45pm in M.A.143

# Registration
Participation is free, but registration is compulsory. 

# References and Related Reading


- Laroche, R., Trichelair, P., and Tachet des Combes, R. (2019). [Safe Policy Improvement with Baseline Bootstrapping](https://proceedings.mlr.press/v97/laroche19a.html). *ICML*, 3652–3661.
- Levine, S., Kumar, A., Tucker, G., and Fu, J. (2020). [Offline reinforcement learning: Tutorial, review, and perspectives on open problems](https://arxiv.org/abs/2005.01643).
- Simão, T. D., and Spaan, M. T. J. (2019a). [Safe policy improvement with baseline bootstrapping in factored environments](https://doi.org/10.1609/aaai.v33i01.33014967). *AAAI*, 4967–4974. 
- Simão, T. D., and Spaan, M. T. J. (2019b). [Structure learning for safe policy improvement](https://doi.org/10.24963/ijcai.2019/479). *IJCAI*, 3453–3459.
- Simão, T. D., Suilen, M., and Jansen, N. (2023). [Safe policy improvement for POMDPs via finite-state controllers](https://doi.org/10.1609/aaai.v37i12.26763). *AAAI*, 212–220.