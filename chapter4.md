# Chapter 4

### Exercise 4.1

In Example 4.1, if π is the equiprobable random policy, what is qπ(11, down)?
What is qπ(7, down)?

#### Answer

qπ(11, down) = r = -1
qπ(7, down) = r + vπ(11) = -1 - 14 = -15

### Exercise 4.2

In Example 4.1, suppose a new state 15 is added to the gridworld just below
state 13, and its actions, left, up, right, and down, take the agent to states 12, 13, 14,
and 15, respectively. Assume that the transitions from the original states are unchanged.
What, then, is vπ(15) for the equiprobable random policy? Now suppose the dynamics of
state 13 are also changed, such that action down from state 13 takes the agent to the new
state 15. What is vπ(15) for the equiprobable random policy in this case?

#### Answer

##### unchanged policy

vπ(15) = 1/4 * (-1 + (-20)) = -5.25

##### changed policy



### Exercise 4.3

What are the equations analogous to (4.3), (4.4), and (4.5) for the action-
value function qπ and its successive approximation by a sequence of functions q0, q1, q2,...?

#### Answer

