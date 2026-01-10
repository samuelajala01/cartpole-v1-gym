What is the Reward function, and what behavior does it incentivize?

The Reward function is like a signal that tells the agent how well it is performing. It is usually in form of a number, 
like +1, -1, -100. The goal of the agent is to maximise the cumulative reward over time. From this, the agent infers 
which actions are the best now, even though it might seem bad, but then gets more total rewards eventually.
<br/>
<br/>
The behaviour the Reward function will incentivize includes:
- Staying within the bounds: Because there is an edge on both sides, the cart can fall off, and the episode ends. 
It would then make sense to Reward the agent when the cart is close to the centre.
- Keeping the pole upright: This makes sense on its own as this is even the goal, you could Reward the agent with
more points and the angle between the pole and the cart gets closer to 90 degrees.
