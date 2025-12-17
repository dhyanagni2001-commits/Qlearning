# Q-Learning with Experience Replay

This project implements a **Q-learning agent with experience replay** for a **finite Markov Decision Process (MDP)**. The goal is to understand reinforcement learning fundamentals, including value updates, replay buffers, and learning from past experiences.

---

## Project Overview
- Implements tabular Q-learning
- Uses experience replay to stabilize learning
- Trains and evaluates an agent on finite MDPs
- Designed for experimentation and analysis

---

## Implementation Details
All implementation is done in:
- `replay_buffer.py` – Experience replay buffer
- `q_learning.py` – Q-learning agent logic

Only these files are modified and graded.

---

## Files Description
- `utils.py` – Utility functions, transition structures, random MDP generator
- `finite_mdp.py` – Definition of a finite-state, finite-action MDP
- `replay_buffer.py` – Stores and samples past transitions
- `q_learning.py` – Q-learning agent with replay-based updates
- `playground.ipynb` – Notebook for local testing and visualization (not graded)

---

## Features Implemented
- Replay buffer with random sampling
- Tabular Q-value updates
- Experience replay–based learning
- Vectorized operations where possible

---

## How to Run / Test
- Test locally using:
  - `playground.ipynb`
  - Random MDPs generated via `generate_random_mdp` in `utils.py`
- Submit through **Vocareum** after verification

---

## Notes
- Do **not** set or modify random seeds
- No external libraries beyond the provided code
- Notebook changes are not graded
- Proper implementation shows improving learning curves over time

---
