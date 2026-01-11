When does an episode terminate, and why?

An episode terminates when/if one or more of the following conditions are met:
- Cart moves beyond 2.4 units from the center
- Pole tilts more than 12° away from the vertical
- When 500 steps are complete: the steps are like actions taken by the agent to balance the pole. If the
- agent balances the pole within the max number of steps - 500, then good.

Why?
This is good because it helps the agent understand what actions prevent it from achieving its goal.

Keep in mind that these constraints are fixed and comes with the cartpole-v1 environment. This makes it
a benchmark for testing balancing algorithms too.
