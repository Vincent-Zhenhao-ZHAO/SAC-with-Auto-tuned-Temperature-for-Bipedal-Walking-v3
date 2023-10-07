# 🤖 SAC with Auto-tuned Temperature for Bipedal Walking v3

## 🚀 Introduction

Welcome to the exploration of bipedal locomotion mastery in the Bipedal-Walking-v3 environment! This project encompasses the application of a modified Soft Actor-Critic (SAC) algorithm as a part of my Reinforcement Learning course, aiming to skillfully navigate through the challenges and complexities of bipedal movement.

## 📜 Abstract from the Paper

> _"This paper implements Soft Actor-Critic(SAC) in both standard and hardcore versions of BipedalWalker-v3 by adjusting the learning rate and reward scale. Both versions achieved over 300 points at episodes 117 and 1296 respectively. While the standard version converged within 200 episodes, it was difficult to determine if the hardcore version converged due to frequent crashes of the NVIDIA CUDA Center (NCC) and limited time. Future work should focus on running the agent in a more stable environment and exploring adaptive learning rate methods to optimize performance in complex environments."_ 

## 🏆 Achievements 

### Standard Environment
Achieved a noteworthy score of **300** at episode **117**, demonstrating a promising convergence in the initial 200 episodes.

![Standard Environment Bipedal Walker](cvhm34-agent-video,episode=1100,score=324.gif)

### Hardcore Environment
Successfully garnered a reward of **300** at episode **1296**, showcasing adept capabilities in navigating through a notably challenging scenario.

![Hardcore Environment Bipedal Walker](cvhm34-agent-hardcore-video,episode=2160,score=304.gif)

## 🛠 Installation and Usage

### Prerequisites
Ensure the availability of the following before proceeding:

- Python 3.x
- [OpenAI Gym](https://gym.openai.com/)
- [PyTorch](https://pytorch.org/)

### Get Started
Execute the following commands in your terminal to set up and run the project:

```bash
git clone [repository_url]
cd SAC-with-Auto-tuned-Temperature-for-Bipedal-Walking-v3
