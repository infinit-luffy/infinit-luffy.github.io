---
title: "Learning from Memory: Decision making by learning associations in the latent space"
collection: publications
excerpt: 'This paper is about unspuervise learning and reinforcement learning'
date: 2024
venue: 'IJCAI'
---

This work is under review on IJCAI-2025

Abstract:
The end-to-end deep reinforcement learning has achieve human-surpassing performance when interacting with a gaming environment. However, the direct use of image data often requires the model to learn the useful information in an high-dimensional feature space, which results in unnecessary memory and computational cost. Inspired by the human hippocampus’s memory processes, we propose two variational self-encoders that separately encodes the background and dynamic features while compensating any missing information through connection encoding. This method relies solely on self-encoders and variational self-encoders, with no additional supervised information. We evaluate our algorithm on the Atari games, demonstrating that it achieves comparable or better performance than using full images when tested with both PPO and DQN in Stable Baselines3.
