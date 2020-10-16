# ros4xavier


# background 
  - to use ROS2 and ROS1  on Xavier at the same time
  - 
# problems
  - Xavier: Ubuntu 18.04
  - ROS2 Foxy can be built/installed from source on 18.04         (foxy supports only 20.04, not 18.04)
  - ROS1 melodic can be installed by apt but it remove python3-rosdep and several packages of ROS2(foxy)
  - ROS1 noetic doesnot support 18.04 and failed in source-building due to python3-pykdl dependency problem (tf_convversions, tf2_geometry_msgs)
  
 # Solution trail at 2020-10-19
  - ROS1 melodic souce build
