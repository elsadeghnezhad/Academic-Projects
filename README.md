# Self-Driving Car Simulation with RL + Vision

## Overview
This project demonstrates a simple **2D self-driving car simulation** using **Reinforcement Learning (DQN)** and **Computer Vision (CNN)**.  
The car learns to navigate a track, avoid obstacles, and stay within lane boundaries using raw camera images as input.

---

## Features
- 2D simulated environment with a track and obstacles
- CNN-based processing of environment images
- Deep Q-Learning (DQN) for learning driving decisions
- Video/GIF recording of the car’s navigation
- Easily extendable to more complex tracks or 3D simulations

---

## Demo
![Demo GIF](run.gif)  
*(Replace with your GIF or video of the agent running)*

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/elsadeghnezhad/self_driving_rl.git
cd self_driving_rl
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
Dependencies include: Python, PyTorch, OpenCV, NumPy

---

## Usage

### Training
```bash
python train.py
```

### Testing
```bash
python test.py
```
The test script will generate a `run.mp4` video showing the agent navigating the track.

---

## Project Structure
```
self_driving_rl/
│
├── README.md
├── environment.py      # 2D environment definition
├── dqn_agent.py        # DQN agent implementation
├── train.py            # Training script
├── test.py             # Testing script and video generation
├── requirements.txt    # Dependencies
└── assets/             # Optional images for environment visualization
```

---

## Tech Stack
Python | PyTorch | OpenCV | NumPy  

---

## Skills Demonstrated
- Reinforcement Learning (DQN)  
- Computer Vision (CNN for image processing)  
- Simulation and environment design  
- Model training and evaluation  
- Data visualization (video/GIF of agent performance)  

---

## Notes
- The environment is designed for **learning and demonstration purposes**; it can be extended to 3D simulators like CARLA.  
- To improve performance, try tuning DQN hyperparameters or designing more complex tracks.