# SoftGym: Benchmarking Deep Reinforcement Learning for Deformable Object Manipulation
**Venue:** Conference on Robot Learning (CoRL)  
**Year:** 2020  
**URL:** https://arxiv.org/abs/2011.07215  
**Lab / University:** Carnegie Mellon University (Xingyu Lin, Yufei Wang, Jake Olkin, David Held)  
**Domain:** Robotics + Deep Reinforcement Learning  
**Date Skimmed:** 2025‑12‑20

## Stop Point Reached
- [X] Abstract
- [X] Introduction
- [X] Figures / Tables (if present)
- [X] Conclusion / Summary

---

## 1) Problem (informal, 1 sentence)
- RL for deformable object manipulation lacks a standardized benchmark for evaluation.  

## 2) Why this problem exists (context)
- Current methods are tested on inconsistent or narrow setups.  
- Hard to compare algorithm performance reliably across tasks and labs

## 3) Vocabulary & terms (list up to 6)
- Environment / Simulation :where the agent interacts (SoftGym is the environment)
- Agent / Policy: The "robot" or decision-maker that chooses actions
- Episode: a sequence of actions until a task ends
- Reward: Feedback signal for agent performance
- Deformable Object: Non-rigid objects(cloth, rope, soft body)
- Observation / State: what the agent perceives at each time step
- Action / Control: Moves or forces applied to manipulate obejcts
- Evaluation Metric: How success is measured (accuracy, efficiency, stabiliy)
- Sim-to-Real: How simulation results transfer to real robots.  

## 4) Solution pattern (choose 1–2)
- Benchmarking/platform + evaluation 

## 5) What this paper is *not* doing
- Not algorithm invention, but a tool to enable research.  

## 6) Why another paper / lab would *cite* this
- To evaluat and compare RL algorithms for deformable object manipulation reliably. 

## 7) One question I now have (no answer)
- How well do results in SoftGym transfer to real-world deformable objects?

