# 🐍 Reinforcement Snake and Food Game from Scratch

A classic Snake Game powered by **Reinforcement Learning**, implemented entirely from scratch in Python — no game engines, no external RL libraries, just pure logic and learning.

---



## 🧠 Overview

This project simulates a snake navigating a grid to eat food and survive as long as possible. The snake is trained using **Reinforcement Learning** techniques (such as Q-learning or Deep Q-Learning) to learn how to make intelligent movement decisions based on the environment.

It serves both as a learning tool and a demonstration of how agents can learn via trial and error using rewards and punishments.

---

## 🚀 Features

- ✅ **Fully Custom Game Engine** (no Pygame or external libraries)
- 🧠 **RL Agent** trained using Q-Learning 
- 🎯 **Goal-oriented Rewards System**
- 📈 Training statistics and optional visualizations
- 🧪 **Play Mode** to test the trained agent


---

## 🤖 Reinforcement Learning Approach

The agent (snake) is trained using one of the following:

- **Q-Learning (Tabular)**: Basic method using a Q-table to store and update action values.


The snake learns:
- When to turn left/right/forward
- How to seek food optimally

---

## 🛠 Installation

Clone the repository and install required dependencies.

```bash
git clone https://github.com/yourusername/reinforcement-snake-game.git
cd reinforcement-snake-game
pip install -r requirements.txt
