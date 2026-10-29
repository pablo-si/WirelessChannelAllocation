# Wireless Channel Allocation

This project studies **wireless channel allocation as a stochastic multi-armed bandit problem**. A base station assigns two users to different channels from a set of five, aiming to maximize the expected sum of their transmission rates.

The project implements the **Upper Confidence Bound (UCB)** algorithm under two feedback models: **aggregate feedback**, where only the total reward is observed, and **per-user feedback**, where the individual transmission rates are available. The objective is to investigate how the feedback available to the learner affects channel selection and learning efficiency.

**Project files:** [Jupyter notebook](RL_1.ipynb) · [Technical report](RL_1.pdf)
