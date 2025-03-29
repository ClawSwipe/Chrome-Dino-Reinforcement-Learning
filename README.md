# Chrome Dino Reinforcement Learning
 
# 🦖 DinoAI - Chrome Dino Game AI with Deep Q-Networks (DQN)

DinoAI is a reinforcement learning (RL) project where an AI agent is trained using **Deep Q-Networks (DQN)** to play the famous **Chrome Dino Game** automatically.

## 🚀 Features
- Uses **Deep Q-Networks (DQN)** for training.
- Implements **stable-baselines3** for reinforcement learning.
- Captures game screen using **mss**.
- Uses **PyTesseract** for OCR-based score reading.
- Automates actions with **pydirectinput**.

## 📌 Installation
Make sure you have Python installed. Then, install the required dependencies:

```sh
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu113
pip install stable-baselines3[extra] protobuf==3.20.*
pip install mss pydirectinput pytesseract
```

## 🎮 How It Works
1. **Screen Capture**: The AI continuously captures the Dino game screen.
2. **State Processing**: Extracts key information using OpenCV and OCR.
3. **Action Selection**: The DQN model decides whether to jump, duck, or run.
4. **Learning**: The AI improves over time by adjusting Q-values based on rewards.

## 🛠 Usage
Run the script and make sure the Dino game is open in Chrome:


## 🏆 Results
- The AI learns to **jump over obstacles** and **maximize score**.
- With enough training, it can achieve near-perfect performance.
- A best model trained is provided as well for testing purposes




