# Reinforcement Learning:
1. trial and error, delayed reward
2. exploration vs exploitation trade-off
# Elements of Reinforcement Learning:
## Main Elements:
1. Agent 
2. Environment
## Sub-Main Elements:
1. Policy
2. Value
3. Reward
4. Action
5. Model

# Definitions:
**Action (A):** All the possible moves that the agent can take
**State (S):** Current situation returned by the environment.
**Reward (R):** An immediate return sent back from the environment to evaluate the last action.
**Policy (π):** The strategy that the agent employs to determine next action based on the current state.
**Value (V):** The expected long-term return with discount, as opposed to the short-term reward R. Vπ(s) is defined as the expected long-term return of the current state sunder policy π.
**Q-value or action-value (Q):** Q-value is similar to Value, except that it takes an extra parameter, the current action a. Qπ(s, a) refers to the long-term return of the current state s, taking action a under policy π.

# Differences:
## Model-Free vs Model based
**Model Free**


**Model Based**



## On-Policy vs Off-Policy
**On-Policy**


**Off-Policy**


## Control Problem vs Prediction Problem
**Control Problem**


**Prediction Problem** 






