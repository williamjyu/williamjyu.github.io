---
layout: page
title: Intrinsic Motivation in RL
description: When does curiosity-driven exploration help, or hurt, cross-task representation transfer?
importance: 1
---

**Does Curiosity Shape Transferable Representations? Intrinsic Motivation as a Representation Learning Mechanism for Cross-Task Transfer in Procgen**

With Zhafira Fawnia, Harshit Aggarwal, Muhiim Ali, and Eugenio Macias · Brown University

An empirical study of when curiosity-driven exploration improves versus harms cross-task representation transfer.

- Researched intrinsic motivation reinforcement learning frameworks (ICM, RND, CFN, NLL-Surprise) across 507 trained checkpoints spanning 12 Procgen games.
- Used PyTorch and an IMPALA-CNN encoder trained with PPO.
- Ran ~700 GPU-hours of experiments on Brown's Oscar HPC cluster, scheduling training, evaluation, and fine-tuning phases.

[Read the paper (PDF)]({{ '/assets/pdf/projects/curiosity-transfer-rl-paper.pdf' | relative_url }})
