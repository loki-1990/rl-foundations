# RL Foundations

This repository contains foundational Reinforcement-Learning implementation, organised into three classic problem settings:

1. Multi-Armed Bandits
2. Dynamic Programming for MDPs
3. Temporal-Difference Control on CliffWalking

## 📂 Repository Structure
rl-foundations/
├─ README.md              # root = repo-level overview (full context)
├─ requirements.txt
├─ .gitignore
└─ assignments/
   ├─ bandits/
   │  ├─ multi_armed_bandits.ipynb
   │  └─ README.md        # specific: ε-greedy, UCB, regret plots
   ├─ dp_mdp/
   │  ├─ career_path_dp.ipynb
   │  └─ README.md        # specific: Policy Eval/Iter, Value Iter, custom env
   └─ td_cliffwalking/
      ├─ cliffwalking_td.ipynb
      └─ README.md        # specific: SARSA, Q-Learning, CliffWalking env

## 🚀 Setup

git clone https://github.com/<your-username>/rl-foundations.git
cd rl-foundations
pip install -r requirements.txt
jupyter lab

## 📘 Contents

- **[Bandits](assignments/bandits/README.md)**  
  ε-greedy and UCB algorithms on multi-armed bandits, analyzing reward and regret.

- **[Dynamic Programming for MDPs](assignments/dp_mdp/README.md)**  
  Policy Evaluation, Policy Iteration, and Value Iteration on custom CareerPath environments.

- **[Temporal-Difference Control (CliffWalking)](assignments/td_cliffwalking/README.md)**  
  SARSA and Q-Learning applied to the classic CliffWalking environment from Gymnasium.

## 🛠️ Skills Demonstrated
- Reinforcement Learning fundamentals
- Exploration vs. Exploitation strategies
- Dynamic Programming methods for MDPs
- Temporal-Difference learning (SARSA, Q-Learning)
- Gymnasium environments
- Python, NumPy, Matplotlib

## For full experiment details and plots:  
- [Bandits](assignments/bandits/README.md)  
- [DP/MDP](assignments/dp_mdp/README.md)  
- [TD Control](assignments/td_cliffwalking/README.md)
