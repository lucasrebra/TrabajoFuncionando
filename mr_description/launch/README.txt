Para lanzar nuestro robot en la simulacion:

In one terminal:

    ROS_PACKAGE_PATH=$HOME/catkin_ws:/opt/ros/kinetic/share
    your launch command as usual. This should successfully launch gazebo
    roslaunch gazebo_ros empty_world.launch

In another terminal:

    ROS_PACKAGE_PATH=$HOME/catkin_ws:/opt/ros/version kinetic-indigo/share
    your spawn command, and then everything should work fine.
    rosrun gazebo_ros spawn_model -file pwd/fable_test.urdf -urdf -x 1 -model fable


