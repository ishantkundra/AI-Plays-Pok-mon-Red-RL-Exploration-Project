# 🎮 AI Plays Pokémon Red – RL Exploration Project

This project applies **Reinforcement Learning** to Pokémon Red to train agents that **explore the game world**, not just win. We experiment with different reward strategies to encourage curiosity and smarter gameplay.

📍 **Texas A&M University – Deep Reinforcement Learning Project**  
👨‍💻 By Ishant Kundra, Rahaan Gandhi, and Aashay Kadakia

---

## 🚀 Project Highlights

- 🧠 **RL Algorithms**: PPO (main), Q-Learning (baseline)
- 🕹️ **Environment**: PyBoy Emulator + Stable Baselines3
- 🧪 **Rewards**:
  - `Original`: Level, health, badges
  - `Curiosity`: Adds exploration rewards
  - `Custom`: Tuned with penalties (e.g., healing spam)

---

## 🧪 Key Results

| Reward     | Exploration | Behavior        |
|------------|-------------|-----------------|
| Original   | 🟡 Moderate  | Passive         |
| Curiosity  | 🟢 Good      | Map coverage improved |
| Custom     | 🔴 Best      | Smart, risky, effective |

---

## ⚙️ How to Run

```bash
# Set up environment
conda create --name pokey python=3.10
conda activate pokey
pip install -r requirements.txt

# Add game ROM
# Rename it to: PokemonRed.gb

# Train PPO agent
python baseline_fast_v2.py

```
##👨‍💻 Authors

**Ishant Kundra**
M.S. Computer Science, Texas A&M University
📧 ishantkundra9@gmail.com

**Rahaan Gandhi**
M.S. Computer Science, Texas A&M University

**Aashay Kadakia**
M.S. Computer Science, Texas A&M University
