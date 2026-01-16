 What assumptions does CartPole make that do NOT hold for real robots?

 - The cartpole environment is very simplified.
 - Noise: the cartpole assumes zero noise when reading inputs from the environment, but in the real world,
 - data from sensors are usually noisy and light have to go through filters first.
 - Lack of Effects: the environment assumes a frictionless plane, as well as zero air resistance. In the real world, there's nothing
  really frictionless, unless the robot is in vacuum, there's usually air resistance on the robot.
 - Zero latency: in this environment, force is applied as soon as the calculation is done. In the real world, it takes a while, there's usually a delay in the signal
   being sent from the brain to the actuators.
