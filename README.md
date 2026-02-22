# Selected Topics in Reinforcement Learning

A selection of talks I've given across three runs of the [Formela Laboratory Seminar](https://is.muni.cz/predmet/fi/jaro2025/iv125) at Masaryk University, Brno. 
These talks span a wide range of advanced RL topics, including off-policy deep RL algorithms, the theoretical foundations of distributional and maximum-entropy RL, and fine-tuning LLMs through direct preference optimization.

## References

Each talk is a synthesis of multiple papers, which are always referenced in the slides. The references at the end of the Off-Policy talk are supplementary reading recommended for seminar attendees.

## Overview

| Topic | Key algorithms and concepts |
|-------|-------------|
| Deep Off-Policy RL | TD3, DDPG, SAC, maximum entropy RL |
| Distributional RL | C51, QR-DQN, Wasserstein distance, quantile regression |
| Direct Preference Optimization | RLHF, KL-regularized RL, deriving the DPO objective |

## Talks

### Deep Off-Policy RL (DDPG, TD3, SAC)
* Introduction to off-policy RL
* Algorithmic challenges and overestimation bias
* Maximum entropy RL, deriving and explaining SAC losses (reparametrization trick)

### Distributional RL
* Theoretical foundations of distributional RL, distributional Bellman operator, Wasserstein distance
* Categorical representation and the C51 algorithm
* Quantile representation and the QR-DQN algorithm
* Analysis of results, advantages, and disadvantages of distributional RL

### Direct Preference Optimization (DPO)
* Phases of training LLMs: pre-training, fine-tuning, RL from human feedback
* Training a reward model, KL-regularized RL, avoiding reward hacking
* DPO ~ fine-tuning with an implicit reward model, deriving the objective from scratch
