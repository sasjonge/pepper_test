Softbank Pepper URDF & Mesh model

Developer : Kensei Demura - kendemu@me.com
	    http://kendemu.blogspot.jp
	 
License : BSD

This is the Softbank pepper URDF & Mesh model for executing pepper in RViz/Gazebo simulator.

Requirements : ROS Groovy or higher (Tested in ROS Indigo)
	       rviz
	      

 To Execute the file,
 $ cd /path/to/pepper_model
 $ roslaunch $(pwd)/launch/display_kendemu.launch model:=$(pwd)/urdf/pepper_robot_model.urdf
