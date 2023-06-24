# URDF-UDM
ROS URDF Robotique - TP 5

Part 1 - Setting up the URDF of the existing robot:

    Create a new ROS package using catkin_create_pkg.
    Place the URDF file in the urdf folder.
    Create a launch file to load the URDF in RViz using the rviz node.

Part 2 - Integrating the URDF with MoveIt:

    Generate the MoveIt package using moveit_setup_assistant.
    Configure the MoveIt package based on the robot's URDF.
    Create a launch file to launch MoveIt with RViz.

Part 3 - Creating services for forward and inverse kinematics:

    Write a ROS node that provides the forward and inverse kinematics services.
    Implement the forward kinematics service function that calculates the end effector pose based on joint positions.
    Implement the inverse kinematics service function that calculates the joint positions based on the end effector pose.
    Advertise the services using the advertiseService() function in the ROS node.
