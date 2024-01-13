# dummy_mission_control

A dummy mission control that runs the Mission Control web server without any dependencies on ROS2.
- Previous dependencies on ROS are now replaced with a stub.
- As part of the simulation, drones are simulated in a separate thread, receiving commands as necessary.