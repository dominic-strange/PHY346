# PHY346

Progress made on development of microscopic model for PHY346.
Two bugs in current state regarding adaptive deceleration function and vehicle behaviour if statements (detailed in report).
If statements responsible for vehicle movement may need overhaul to catch behaviour being missed currently by the algorithm.

Both cars_move_explain and cars_move_data take same inputs:

cars_move_explain(v_min, v_max, dt, num, v_ideal_base, tot_timeframe, Adaptive_Decel)

v_min = min allowed velocity of vehicles generated (km/h)

v_max = max allowed velocity of vehicles generated (km/h)

dt = timestep between vehicle movements (recommended to keep to 1 second as algorithm is optimised around this) (s)

v_ideal_base = velocity for vehicles to reach in slowest lane (km/h)

tot_timeframe = total timeframe over which the simulation is carried out (s0

Adaptive_Decel = toggles adaptive deceleration (True/False, recommended to set to false due to presence of bug)

All code was developed in cocalc in Python 3 (Anaconda 2019)
