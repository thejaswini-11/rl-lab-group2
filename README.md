# Exploring DQN Extensions on MinAtari-Breakout

This project implements and compares DQN extensions to understand their individual and combined effects on learning performance:

- **Vanilla DQN** - Baseline implementation
- **Double DQN** - Reduces overestimation bias by decoupling action selection from evaluation
- **Dueling DQN** - Separates state value and action advantage estimation
- **Multi-step DQN** - Uses n-step returns for better credit assignment
- **Combined Extensions** - Evaluates combined effects of multiple improvements when applied together

## Environment 

**MinAtar Breakout** - A simplified version of the classic Atari Breakout game
- State space: 10×10 grid with 4 channels
- Action space: 3 actions (Move Left, Stay, Move Right)
- Objective: Break bricks by bouncing the ball with the paddle

## References

1. [Dueling Deep Q-Network article – EmergentMind](https://www.emergentmind.com/topics/dueling-deep-q-network-dueling-dqn)
2. [Hessel et al., 2018. Rainbow: Combining Improvements in Deep Reinforcement Learning (arXiv)](https://arxiv.org/abs/1710.02298) – Referenced for combined RL enhancements and methods applied in this project.
3. [ChatGPT by OpenAI](https://chat.openai.com/) – Used for guidance 
