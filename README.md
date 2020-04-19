# turtlebot3_in_ROS_melodic
Tutorial to use turtlebot3 in ROS melodic
## Follow the following instructions to install turtlebot3 in ROS melodic 
### Setup:
  (Process assumes ros, git and other dependencies are installed)
  1. Run the command `git clone https://github.com/neelotpal-d/turtlebot3_in_ROS_melodic` in any directory
  2. Then run `source turtlebot3_in_ROS_melodic/turtlebot3_melodic_setup.bash`
  3. Wait for process to complete
  4. If successfull you shall be in ~/wanderbot
  3. Installation and setup is complete
## To launch a turtlebot in Gazebo follow these steps:
(Needs Gazebo and other dependencies to be installed already)

### With the included bash script:
  1. Go to the direcotry where you ran the command 1 of [setup](https://github.com/neelotpal-d/turtlebot3_in_ROS_melodic/blob/master/README.md#setup)
  2. Run the command source `turtlebot3_in_ROS_melodic/turtle_gazebo.bash`
  3. Wait for gazebo to start with turtlebot in it

### Without the script
   1. Run the command `export TURTLEBOT3_MODEL=burger`
   2. Then launch gazebo with turtlebot3 by `roslaunch turtlebot3_gazebo turtlebot3_world.launch`
   3. Note that you must source the bash file in the workspace before starting.
 
