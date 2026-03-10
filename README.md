# 314511067_Exercise1.12
# PPO for MountainCar-v0

本專案使用 **PyTorch** 實作 **Proximal Policy Optimization (PPO)** 演算法，並採用 **Actor-Critic 架構** 來解決 OpenAI Gym 的 **MountainCar-v0** 環境。

PPO 透過 **importance sampling ratio** 與 **clipped objective** 來限制 policy 更新幅度，使訓練過程更加穩定。
Actor network 負責輸出動作機率分佈，Critic network 則用來估計狀態價值並計算 advantage。

## Requirements

```bash
pip install torch gym tensorboardX numpy matplotlib
```

## Run

```bash
python ppo_mountaincar.py
```
