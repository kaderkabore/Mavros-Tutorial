# Mavros-Tutorial


 This provide a quick tutorial about launching mavros and px4.  
 # Open the terminal
 -cd path_to_cloned_repo/src/Firmware\
 -make px4_sitl gazebo

Open another terminal window or tab, and start MAVROS node using

 -roslaunch mavros px4.launch fcu_url:="udp://:14540@192.168.0.103:14557"\
 
 From here you will have gazebo launched with a drone.
 
 Now we can write the controller script.\
-Create an new ros simple package (http://wiki.ros.org/ROS/Tutorials/CreatingPackage) \
-create a new python script and paste the code from simple_controller.py in it \
-Save and Don't forget to (chmod +x filename).\
-Run the script  (./filename)


  # Now you can see the drone takeoff to an altitude of 3 m.
  The code may look confusing but still feel free to play with the altitude,x and y variable in the code.The drone will fly to different dirrections and altitudes.
  
If you have any question please reach us.Next week we may try to explain to code and the architecture in detail.
 
 # HAVE FUN AND ENJOY


You can also refer to these tutorials.

https://dev.px4.io/master/en/simulation/gazebo.html \
https://edu.gaitech.hk/gapter/mavros-basics.html \
https://akshayk07.weebly.com/offboard-control-of-pixhawk.html.
