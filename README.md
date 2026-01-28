# RL Goal Seeker


https://github.com/user-attachments/assets/704f2af8-9eda-43ac-ae36-ff8bdceb275e


# Goal Seeker — Reinforcement Learning Simulator

**Goal Seeker** is a lightweight, browser-based reinforcement learning simulator for experimenting with prediction and control algorithms in a grid-world environment. It provides a visual, interactive way to observe how an agent learns to reach a goal using classic RL methods such as **Q-Learning**.

The project is intentionally simple and framework-free, making it ideal for learning, teaching, and rapid experimentation.

---

## Features

- **Reinforcement Learning Algorithms**
  - Q-Learning (tabular)
  - SARSA (UI-ready; easy to plug in)

- **Grid-World Environment**
  - Obstacles, empty cells, and terminal goal states
  - Configurable rewards

- **Interactive Simulator**
  - Step through learning one action at a time
  - Run full episodes at adjustable speed
  - Reset environment and policy instantly

- **Live Hyperparameter Control**
  - Learning rate (α)
  - Discount factor (γ)
  - Exploration rate (ε)

- **Real-time Stats**
  - Episode count
  - Steps per episode
  - Last received reward

- **Modern UI**
  - Responsive layout
  - Light / dark theme toggle
  - Keyboard shortcuts

---

## How It Works

1. The **Agent** exists in a discrete grid environment.
2. At each step:
   - The agent selects an action using an RL algorithm.
   - The environment returns a reward.
   - The algorithm updates its value estimates.
3. Learning continues until the agent reaches the goal state.

The simulator cleanly separates:
- **Environment** (`Grid`, `Cell`)
- **Learning algorithm** (`Algorithm`, `QLearning`)
- **Visualization** (`Visualizer`)
- **Control logic** (`Simulator`)

---

## Running the Project

### Option 1: Open directly

Open `index.html` in a modern browser.

> Some browsers restrict ES modules from local files.  
> If you see errors, use a local server.

### Option 2: Local server (recommended)
 
## Clone the repository 
- git clone `repo-url`
- cd `project-folder`

## Start a local server
- npx http-server

## Open in your browser
- `http://localhost:8000`






