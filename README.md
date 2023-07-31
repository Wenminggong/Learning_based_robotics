# Learning-based Robotics
This repo collets a series of papers and projects about robotics, and which focuses mainly on learning-based topics of robotics.

This repo will gradually be expanded, now it contains topics as follow:
* [ ] RL-based UAV
  * [ ] single-agent
  * [ ] multi-agents

* [ ] Popular UAV Simulators


## Popular Simulators
* 2016. [RotorS](https://www.researchgate.net/publication/309291237_RotorS_-_A_Modular_Gazebo_MAV_Simulator_Framework)
  * based on gazebo, not photorealistic 
  * design drone model and sensors using parameters of real drone
  * implemente state estimation and geometric control to support high-level tasks, e.g., obstacle avoidance and path planning
  * the algorithm tested in simulator can transfer to real drone directly (just for their own MAV)
  * suitable for model-based planning and control
* 2018. Airsim
* 2019. FightGoogles
* 2021. Gym-pybullet-drone
* 2021. FlightMare
* [2022. PRL4Airsim](https://github.com/SaundersJE97/PRL4AirSim)
  * based on Airsim
  * using Blueprint system to ignore overlapping events between uavs and make uavs hide in the scene capture
  * new image-get api to reduce time cost
  * just design for single uav
  * no comparation with other uav simulators which support RL training

## Labs
* [UZH, Robotics and Perception Group.](https://rpg.ifi.uzh.ch/index.html)
  * event-based camera
  * drone racing
  * learning-based drone agile flight