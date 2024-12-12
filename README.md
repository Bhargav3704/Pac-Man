# **Reinforcement Learning for Pac-Man**
Train an AI agent to play the **Pac-Man game** using Deep Q-Learning (DQN).

---

## **Project Overview**
This project uses **Reinforcement Learning (RL)** to train an agent in the **Pac-Man environment**. The agent learns optimal actions to maximize its score using Q-Learning with a deep neural network (DQN).

---

## **Tools and Libraries**
- **Python**: Programming language  
- **OpenAI Gym**: Environment setup  
- **NumPy**: Numerical computations  
- **PyTorch / TensorFlow**: Deep learning models  
- **Matplotlib**: Visualizing results  
- **Collections/Deque**: Experience Replay Buffer  
- **OpenCV** *(optional)*: Image preprocessing  

---

## **Environment Details**
- **Game**: `MsPacman-v0` (OpenAI Gym)  
- **State Space**: Raw pixel input or pre-processed states  
- **Action Space**:  
  - `UP`, `DOWN`, `LEFT`, `RIGHT`, `NO ACTION`  
- **Rewards**:  
  - Eating food: +10  
  - Eating ghosts/pellets: +100  
  - Game completion: +500  
  - Losing life: -50  

---

## **Reinforcement Learning Methodology**
1. **Deep Q-Learning (DQN)**:  
   Approximates Q-values using a neural network.  
2. **Experience Replay**:  
   Samples past experiences to stabilize training.  
3. **Epsilon-Greedy Exploration**:  
   Balances exploration vs exploitation.  
4. **Soft Target Network Updates**:  
   Gradual updates to the target Q-network:  
   \[
   \theta_{\text{target}} = \tau \theta_{\text{online}} + (1 - \tau) \theta_{\text{target}}
   \]  

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


