# Traffic Optimization Project To-Do

- [x] If an agent reach its destination remove its collision, give it full reward thereon

- [x] Reward for an agent: 2 - current distance between agent and its destination 

- [x] Punishment for an agent: true if it collides with an agent or a wall

- [x] Observation for an agent: Its velocity and position + walls relative position + other agents relative position and velocity

- [x] Run the DPG algorithm in this settings

- [x] Observation need to be modified, agents should be able to sense their enviorenment up to a fixed distance

  - [x] agents' sensors measure the distance from landmarks
  - [x] agents' sensors measure the distance from eachother

- [x] Observation need to be modified, sensors are not enough, agents should use their position, velocity and destination also

- [x] Stop agents when they reach their destination

- [x] Stop agents when they collide with an object, no further reward

- [ ] Make every agent identical, train one network to be used for all agents 

- [x] Agents should have different speeds in each episode, randomly

- [x] Fix the overlapping positions at the reset time of environment 

- [x] Modify reward function

  

##### Extras

- [x] Change the observation (partial observation)
- [x] Add not moving option to the action space
- [ ] Try to modify the RL algorithm 

##### Notes

- 80 steps is required for reaching to the destionation with perfect policy, no collision, longest road. 

