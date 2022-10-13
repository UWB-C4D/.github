# UWB-C4D project repositories

Droneport (DP) is a system for autonomous drone battery management. It complies with a reference architecture, dealing with drone power management, more precisely, battery management. Regarding the reference architecture, the DP consists of a battery management unit for charging and storage, a robotic manipulator for an automatic battery exchange, a data link to the drone, telemetry data, and a human-machine interface (HMI) for remote command and control. Power and storage management building blocks are implemented in Droneport, with a datalink connection to the outside world. Users can use telemetry data via MAVLink protocol to monitor the state of the DP. The DP acts autonomously, it monitors the state of the batteries, controls the battery exchange and charging, provides necessary navigation information for drone landing, and broadcasts the status of the remaining batteries. 

Software components of Droneport system are included in following repositories:
- [DronePort Traffic Control](https://github.com/UWB-C4D/droneport_traffic_control)</li>
  - [simple_orchestrator.ipynb](https://github.com/UWB-C4D/droneport_traffic_control/blob/main/simple_orchestrator.ipynb) includes the DronePort orchestrator with a demonstration of its use. The DP Orchestrator is used to schedule battery changes for several drones depending on the occupancy and capacity of the battery charge stations.</li>
  - A nonlinear time-continous optimal control problem of trajectory planning considering the battery state of charge is solved in [trajectory_planner.ipynb](https://github.com/UWB-C4D/droneport_traffic_control/blob/main/trajectory_planner.ipynb). The problem is transcribed using chebyshev pseudospectral collocation method to nonlinear program (NLP), which is solved with IPOPT solver.</li>



