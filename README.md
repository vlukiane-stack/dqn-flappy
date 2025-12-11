# DQN Flappy Bird Project

This repository implements a Deep Q-Network (DQN) agent for the Flappy Bird environment using PyTorch, based on the tutorial structure demonstrated in class.

## Project Files

- `agent.py` — defines the DQN agent and handles model logic.
- `dqn.py` — main script to initialize the environment and run training.
- `experience_replay.py` — memory buffer for experience sampling.
- `hyperparameters.yml` — contains key configuration values for DQN training.
- `pyproject.toml` — dependency and environment file generated via **uv**.
- `.python-version` — specifies Python version **3.11**.

## Runs Folder

The `runs/` directory contains materials from the final recorded training session:
- `training_2025-12-11.log` — log of training progress conducted on **December 11, 2025 (10:00 AM – 1:00 PM)**.
- `checkpoint_best.pt` — saved model weights for the best-performing run.
- `config.yaml` — hyperparameters used during the session.

## Notes

This project was prepared for submission in compliance with the assignment requirements:
- Includes virtual environment setup (`pyproject.toml` and `.python-version`).
- Contains a structured `runs` directory with all required elements.
