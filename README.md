As a part of a broader exploration into path planning algorithms, I undertook a project focused on achieving autonomous navigation in a known environment.
Leveraging the capabilities of the Gazebo simulator, my objective was to enable a TurtleBot 3 robot to autonomously navigate within a mapped environment while avoiding obstacles.

KEY STEPS
Environment Mapping: I began by employing SLAM (Simultaneous Localization and Mapping) navigation techniques to map the environment. Through the integration of sensor data and robot movements, I created a detailed map of the surroundings.

Map Storage: Once the mapping process was completed, I stored the generated map for later reference. This step ensured that the robot had access to a precise representation of the environment during the navigation phase.

Navigation Setup: Using Rviz, a visualization tool commonly used in robotic applications, I set up the navigation parameters for the TurtleBot 3. This involved configuring the robot's trajectory and defining obstacle avoidance strategies based on the stored map data.

Autonomous Navigation: With the navigation parameters in place, I initiated the autonomous navigation sequence. The TurtleBot 3 utilized the stored map to navigate within the known environment, dynamically adjusting its path to avoid obstacles encountered along the way.
