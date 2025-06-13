
# 🦖 DinoAI using Reinforcement Learning

A Reinforcement Learning (RL) framework for training an AI agent to play the Chrome Dino game autonomously using screen capture, optical character recognition (OCR), and a custom OpenAI Gym-compatible environment.

## Project Overview

This project demonstrates how an RL agent can learn to play the Chrome Dino game by interacting with a custom environment and learning from rewards. It integrates screen capture, preprocessing, and simulated keyboard inputs to create a complete game-playing pipeline.

### Features

- Custom OpenAI Gym-compatible environment
- Real-time interaction with the Chrome Dino game
- Screen capture to extract game state
- Frame preprocessing for efficient RL input
- Reward system to incentivize survival and obstacle avoidance
- Agent training using popular RL algorithms (PPO, DQN, etc.)

---

## 🔧 Technologies Used

- Python 3.9+
- OpenAI Gym (custom environment)
- NumPy, OpenCV
- PyAutoGUI / PyDirectInput (for key simulation)
- TensorFlow / PyTorch (agent models)
- Stable-Baselines3 (optional)
- Tesseract OCR (optional, for any text recognition)

