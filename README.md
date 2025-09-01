> **Course & Semester:** <Reinforcement Learning, Semester X>

## Overview
A lightweight RL agent for a simplified poker environment (partial information).

## Topics Covered
MDP design and environment API, epsilon-greedy exploration, tabular Q-learning or minimal policy-gradient baseline, evaluation vs random/heuristics.

## How to Run
```bash
python -m venv .venv
pip install -r requirements.txt
python src/train.py --episodes 50000
python src/eval.py --policy qlearn
