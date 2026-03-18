# 🚇 Subway Agent

A reinforcement learning project where an agent learns to play a Subway Surfers–like game by observing the screen, processing visual input, and improving its decisions over time.

---

## 📌 Project Overview

This project explores how reinforcement learning can be applied to a real-time game environment.

The agent:

* captures the game screen
* processes image data
* selects actions (move, jump, dodge)
* learns from rewards to improve performance

The goal is to train an intelligent agent that can survive longer and achieve higher scores through continuous learning.

---

## ⚙️ Features

* Reinforcement learning training pipeline
* Real-time game environment interaction
* Image preprocessing using OpenCV
* Neural network-based decision making
* Replay memory for stable learning
* Advanced techniques:

  * N-step learning
  * Eligibility traces
* Separate scripts for training and evaluation

---

## 📂 Project Structure

```
subway_agent/
│
├── README.md
├── requirements.txt
├── .gitignore
├── train.py
├── evaluate.py
├── images/
├── logs/
├── checkpoints/
├── src/
│   ├── action.py
│   ├── env.py
│   ├── neural_net.py
│   ├── replay_memory.py
│   ├── moving_avg.py
│   ├── n_step.py
│   ├── preprocess_image.py
│   ├── eligibility_trace.py
│   ├── fast_capture.py
│   └── start_game.py
```

---

## 🧠 How It Works

1. The environment captures the game screen
2. The image is preprocessed
3. The neural network predicts the best action
4. The agent performs the action in the game
5. The result is stored in replay memory
6. The model learns from past experiences

---

## 🛠️ Technologies Used

* Python
* Reinforcement Learning
* PyTorch
* OpenCV
* NumPy
* MSS (screen capture)

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/pavan0118/subway_agent.git
cd subway_agent
```

Create virtual environment:

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Train the agent:

```bash
python train.py
```

### Run trained agent:

```bash
python evaluate.py
```

---

## 📊 Learning Outcomes

* Understanding reinforcement learning workflow
* Designing modular AI systems
* Working with real-time image input
* Implementing replay memory and training loops
* Structuring scalable Python projects

---

## 🔮 Future Improvements

* Improve reward function
* Add performance visualization graphs
* Train for longer episodes
* Optimize neural network architecture
* Add model saving/loading improvements

---

## 👨‍💻 Author

**Pavan Kumar Reddy**
TU Dresden Student
Aspiring AI & Software Developer

---

## ⭐ Notes

This project is part of my journey in learning:

* Artificial Intelligence
* Reinforcement Learning
* Computer Vision

---

## 🙌 Contributions

Feel free to fork this repository and improve it!
