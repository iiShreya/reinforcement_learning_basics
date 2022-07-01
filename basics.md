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

![Alt Text](https://lcalem.github.io/imgs/sutton/rl_basics.png)


# Definitions:
**Action (A):** All the possible moves that the agent can take\
**State (S):** Current situation returned by the environment.\
**Reward (R):** An immediate return sent back from the environment to evaluate the last action.\
**Policy (π):** The strategy that the agent employs to determine next action based on the current state.\
**Value (V):** The expected long-term return with discount, as opposed to the short-term reward R. Vπ(s) is defined as the expected long-term return of the current state sunder policy π.\
**Q-value or action-value (Q):** Q-value is similar to Value, except that it takes an extra parameter, the current action a. Qπ(s, a) refers to the long-term return of the current state s, taking action a under policy π.

# Differences:
## Model-Free vs Model based
**Model Free**
These algorithms seek to learn the consequences of their actions through experience. Such an algorithm will carry out an action multiple times, learn from its actions and will adjust the policy (the strategy behind its actions) for optimal rewards, based on the outcomes.

Eg, Self-Driving Cars.


**Model Based**
In such an algorithm, an agent tries to understand its environment and creates a model for it based on its interactions with this environment. In such a system, preferences take priority over the consequences of the actions i.e. the greedy agent will always try to perform an action that will get the maximum reward irrespective of what that action may cause.

Eg, Playing Chess


## On-Policy vs Off-Policy
**On-Policy**
Such an algorithm uses the same policy for Acting and Updating.

**Off-Policy**
Such an algorithm uses a diffrent policy for Acting and Updating.

Eg, In Q-Learning Algorithm:
Acting Policy: Epsilon Greedy Policy
Updating Policy: Greedy Policy for selecting the best next-state action value to update the Q-value.

## Control Problem vs Prediction Problem
**Prediction Problem** 
Prediction requires being able to compute or estimate the consequences of an action. In the typical model-free setting, prediction tasks usually mean estimation of values of states, or action values of state-action pairs.

**Control Problem**
Control requires the ability to choose a decision. Without control, agents would never act.





