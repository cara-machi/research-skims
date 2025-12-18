# Paper Skim Notes — [PILCO: A Model-Based and Data-Efficient Approach To Policy Search ]
**Venue:** ICML
**Year:** 2011
**URL:** https://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf?utm_source=chatgpt.com
**Domain:** [Robotics]  
**Date Skimmed:** 2025-12-18

## Stop Point Reached
- [X] Abstract
- [X] Intro
- [X] Figures
- [X] Conclusion

---

## 1) Problem (informal, 1 sentence)
- RL methods which require tens or hundreds are not suitable for low-cost robots.

## 2) Why this problem exists (context)
- Model bias: learned models of the environment can be inaccurate, affecting policy performance.  
- Data efficiency: standard RL methods require many interactions with the environment, which is costly in robotics.

## 3) Vocabulary & terms (list up to 6)
- Policy: a mapping from state to actions
- Reward: feedback signal evaluating action outcomes
- Iteration: repeated update step during learning
- Policy search: method to improve the policy directly
- Episode: sequence of states and actions until termination
- Exploration vs Exploitation: trade-off between trying new actions vs using known good actions. 


## 4) Solution pattern (choose 1–2)
- Modeling
- Learning

## 5) What this paper is *not* doing
- Does not introduce a new benchmark or dataset.
- Does not provide low-level code. 

## 6) Why another paper would *cite* this
- Introduces a **data-efficeinty, model-based policy search method** for RL.
- Shows a way to **reduce model bias** when learning policies. 
- Serves as a reference for **probabilistic model-based RL in robotics**.

## 7) One question I now have (no answer)   
- How efficient is PILCO in practice?
- Are there constraints on its use (e.g., environment type, number of trials)?
- Is there accessible code to try it out?
