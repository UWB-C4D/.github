# UWB-C4D project repositories

## [DronePort Traffic Control](https://github.com/UWB-C4D/droneport_traffic_control)

[simple_orchestrator.ipynb](https://github.com/UWB-C4D/droneport_traffic_control/blob/main/simple_orchestrator.ipynb) includes the DronePort orchestrator with a demonstration of its use. The DP Orchestrator is used to schedule battery changes for several drones depending on the occupancy and capacity of the battery charge stations.

A nonlinear time-continous optimal control problem of trajectory planning considering the battery state of charge is solved in [trajectory_planner.ipynb](https://github.com/UWB-C4D/droneport_traffic_control/blob/main/trajectory_planner.ipynb). The problem is transcribed using chebyshev pseudospectral collocation method to nonlinear program (NLP), which is solved with IPOPT solver.
